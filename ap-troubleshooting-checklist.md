
# Wireless Access Point Troubleshooting

This is a simple checklist for checking wireless access point issues using Cisco Catalyst Center.

## 1. Check Access Point Status

- Open Cisco Catalyst Center.
- Search for the affected access point.
- Check whether it is online or offline.
- Review its health and available alerts.

## 2. Check Device Information

- Confirm the correct access point is selected.
- Review the last reported status.
- Check whether other access points have similar issues.

## 3. Check Network Connectivity

- Check the switch connected to the access point.
- Verify the switch port status.
- Check for network connectivity problems.
- Review relevant switch logs if needed.

## 4. Investigate the Issue

- Check whether the problem affects one access point or several.
- Review alerts and available device information.
- Record the findings.
- Escalate to the relevant network team if required.

## Useful Cisco Switch Commands

| Command | Purpose |
|---|---|
| `show interfaces status` | Check switch port status |
| `show interfaces description` | Identify connected ports |
| `show logging` | Review switch logs |
| `show power inline` | Check PoE status on supported switches |

## Note

This checklist is for general troubleshooting documentation. Actual steps may vary depending on the network environment and access point model.
