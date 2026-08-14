#Overview of SRE

## Security and access controls

The SRE is hosted on premises. Each project environment is configured to provide the infrastructure, software and tools required to work collaboratively on sensitive research data. Secure virtual desktops enable researchers to work with sensitive data while maintaining greater control and protection. Data is stored separately for each research project and can only be accessed by the team assigned to that environment.

The SRE has enhanced security features to protect project data and is designed to enable data governance within projects using role-based responsibilities and access controls. 

### Multi-tiered security

<ul>
    <li>Aligned with University security standards</li>
    <li>Project data is encrypted</li>
    <li>Auditable data import (ingress), access and export (egress)</li>
    <li>Each project environment is isolated from each other, as well as from the internet and other University systems, except where needed (e.g., to provide access or to maintain security updates).
        <div style="border-left: 4px solid #00caef; padding-left: 12px;">
        SRE users cannot access the internet (unless approved), copy/paste or drag and drop into or out of the project environment, or mount a USB or local drive.
        </div>
    </li>
    <li>Enhanced session security to protect project data.
        <li>You will be logged out of the project environment **after 15 mins of inactivity**</li>
        <li>The VM connection will be closed **after 10 minutes of inactivity**</li>
        <li>If you have been logged out, you will be prompted to log in and enter two-factor authentication again to continue.</li>
    </li>
</ul>

### Access controls

<ul>
    <li>Secure web portal access via web browser</li>
    <li>Access requires two-factor authentication for authorised project team members</li>
    <li>Role-based controlled access and rights based on project needs
        <div style="border-left: 4px solid #00caef; padding-left: 12px;">
        Each role can be held by one or more project team members. A project team member can hold more than one role.
        </div>
    </li>
</ul>

The following table summarises the responsibilities for each project role in the SRE.

<table class="role-table">
<thead>
<tr>
    <th>Role</th>
    <th>Ingress</th>
    <th>Egress</th>
    <th>VM Access</th>
    <th>Manage Users</th>
</tr>
</thead>
<tbody>
<tr>
    <th>Data Custodian</th>
    <td>Direct</td>
    <td>Direct</td>
    <td class="centre"><span class="yes">✓</span></td>
    <td class="centre"><span class="yes">✓</span></td>
</tr>
<tr>
    <th>Researcher</th>
    <td>Request</td>
    <td>Request</td>
    <td class="centre"><span class="yes">✓</span></td>
    <td class="centre"><span class="no">✕</span></td>
</tr>
<tr>
    <th>Ingress Approver</th>
    <td>Approve</td>
    <td class="centre"><span class="no">✕</span></td>
    <td class="centre"><span class="yes">✓</span></td>
    <td class="centre"><span class="no">✕</span></td>
</tr>
<tr>
    <th>Egress Approver</th>
    <td class="centre"><span class="no">✕</span></td>
    <td>Approve</td>
    <td class="centre"><span class="yes">✓</span></td>
    <td class="centre"><span class="no">✕</span></td>
</tr>
</tbody>
</table>


