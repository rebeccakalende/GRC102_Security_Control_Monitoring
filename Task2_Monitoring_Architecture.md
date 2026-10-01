# Task 2: Monitoring Architecture and Automation

## Organisation: Meridian Digital Services (MDS)

## 2.1 Purpose

Meridian Digital Services requires a monitoring architecture that brings together security telemetry, control evidence and management information from its hybrid technology environment.

The proposed architecture reduces dependence on manual checking by collecting evidence from identity systems, endpoints, cloud platforms, vulnerability-management tools, backup systems, applications, network infrastructure and third-party services.

The collected information is analysed through security and monitoring platforms and converted into actionable information for control owners, security management, senior management and the Board.

---

## 2.2 Proposed Monitoring Architecture

### Architecture Flow

```text
                    SECURITY & CONTROL EVIDENCE SOURCES
                                      |
        ---------------------------------------------------------
        |          |          |          |          |            |
      IAM       Endpoints    Cloud      Network   Apps/DBs   Third Parties
        |          |          |          |          |            |
        ---------------------------------------------------------
                                      |
                                      v
                         LOGGING & TELEMETRY LAYER
                                      |
                         ------------------------
                         |                      |
                    SIEM Platform          Security Tools
                         |                      |
                         |          ---------------------------
                         |          |       |       |         |
                         |         EDR    VM     CSPM     DLP
                         |                  |
                         --------------------
                                      |
                                      v
                         ANALYTICS & CORRELATION
                                      |
                         ------------------------
                         |                      |
                    Automated Alerts       Control Metrics
                         |                      |
                         ------------------------
                                      |
                                      v
                       CONTROL MONITORING REGISTER
                                      |
                 ---------------------------------------
                 |                 |                   |
            Control Owners   Security Governance   Risk / Compliance
                 |                 |                   |
                 ---------------------------------------
                                      |
                                      v
                         MANAGEMENT REPORTING
                                      |
                         ------------------------
                         |                      |
                    Senior Management         Board
