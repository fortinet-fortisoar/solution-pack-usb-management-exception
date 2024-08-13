| [Home](../README.md) |
| -------------------- |

# Installation

1. To install a solution pack, click **Content Hub** > **Discover**.
2. From the list of solution pack that appears, search **USB Approval System**.
3. Click the **USB Approval System** solution pack card.
4. Click **Install** on the lower part of the screen to begin the installation.

## Prerequisites

The **USB Approval System** solution pack depends on the following solution packs that are installed automatically &ndash; if not already installed.

| Solution Pack Name | Version          | Purpose                                                  |
|:-------------------|:-----------------|:---------------------------------------------------------|
| SOAR Framework     | v2.0.0 and later | Required for Incident Response modules                   |

# Configuration

For optimal performance of the **USB Approval System** solution pack, you must configure:

-  Fortinet FortiEDR connector to moving collectors
    - To configure and use the Fortinet FortiEDR, refer to [Configuring Fortinet FortiEDR](https://docs.fortinet.com/document/fortisoar/2.0.0/fortinet-fortiedr/888/fortinet-fortiedr-v2-0-0#Configuration_parameters)

- An email ingestion process to periodically read emails from a designated inbox and convert them into alerts in FortiSOAR
    - To configure and use the Microsoft Exchange connector for email ingestion, refer to [Configuring Exchange Connector](https://docs.fortinet.com/document/fortisoar/3.4.0/exchange/1/exchange-v3-4-0#Configuring_the_connector)

-  Active Directory connector to get requester and manager details
    - To configure and use the Active Directory, refer to [Configuring Active Directory](https://docs.fortinet.com/document/fortisoar/2.4.0/active-directory/777/active-directory-v2-4-0#Configuration_parameters)


# Next Steps

| [Usage](./usage.md) | [Contents](./contents.md) |
|---------------------|---------------------------|