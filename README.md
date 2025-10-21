🛡️ Sophos Peripheral Control Policy
🎯 Objective

Block all unauthorized USB storage devices and allow only one authorized (personal) pendrive for use my device.

⚙️ Policy Configuration Details

Policy Name: Peripheral Control - USB Restriction

Location: Sophos Central → Endpoint Protection → Policies → Peripheral Control

Policy Type: Endpoint Policy

Scope: Applies to all users and devices

Policy Status: ✅ Active

🚫 Block Settings

Category: Storage Devices (USB/External Drives)

Action: Block Access

Applies To: All USB Storage Devices

✅ Whitelisted Device

Device Type: USB Storage

Access: Allowed

Device Model / Serial Number: (Add your pendrive model or serial here, e.g., SanDisk Ultra 3.2 – SN: xyz)

Description: Authorized personal pendrive approved for data transfer

📋 Policy Behavior

Blocks all unapproved pendrives automatically.

Only the whitelisted pendrive is accessible on endpoints.

Any attempt to use an unauthorized device will trigger a block event logged in Sophos Central.


Verify device serial number under:
Endpoint → Events → Peripheral Control Logs
