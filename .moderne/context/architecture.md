# Architecture

## FINOS CALM architecture diagram

FINOS CALM (Common Architecture Language Model) architecture diagram showing services, databases, external integrations, and messaging connections. Use this to understand the high-level system architecture and component relationships.

## Data Tables

### Server configuration

**File:** [`server-configuration.csv`](server-configuration.csv)

Server configuration properties extracted from application.properties/yml.

| Column | Description |
|--------|-------------|
| Source path | The path to the configuration file. |
| Server port | The server port (default: 8080). |
| SSL enabled | Whether SSL/TLS is enabled. |
| Context path | The servlet context path. |
| Protocol | The protocol (HTTP or HTTPS) based on SSL configuration. |

