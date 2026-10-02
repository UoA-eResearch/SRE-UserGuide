# Data Storage

Each SRE project includes a set of default storage locations to support secure data management, collaboration and controlled data transfer (ingress and egress). Additional folders and customised folder structures can be configured during project onboarding.

Storage is divided into <code>personal</code> and <code>project-shared</code> areas. Personal folders are intended for individual use, while project-shared folders enable collaboration across the project team.

The table below provides an overview of the default storage folders available within each project.

<table class="role-table">
<thead>
<tr>
    <th>Folder name</th>
    <th>Access</th>
    <th>Who can Access</th>
    <th>Purpose</th>
    <th>Notes</th>
</tr>
</thead>
<tbody>
<tr>
    <th>project-personal (<code>username-r</code>)</th>
    <td>Read/Write (own folder)</td>
    <td>Individual researcher (Data Custodian has full access)</td>
    <td>Private working space for individual research users</td>
    <td>Contains <code>ingress</code> and <code>egress</code> subfolders</td>
</tr>
<tr>
    <th>data-custodian (<code>username-dc</code>)</th>
    <td>Read/Write</td>
    <td>Data Custodians</td>
    <td>Used for direct data ingress/egress and data management</td>
    <td>Contains <code>ingress</code> and <code>egress</code> subfolders</td>
</tr>
<tr>
    <th><code>project-rw</code></th>
    <td>Read/Write</td>
    <td>All project users</td>
    <td>Shared working directory for collaboration</td>
    <td>Files can be edited by all users</td>
</tr>
<tr>
    <th><code>project-ro</code></th>
    <td>Read-only</td>
    <td>All project users (Data Custodian has full access)</td>
    <td>Stores raw or source data</td>
    <td>User must copy files out before editing</td>
</tr>
<tr>
    <th><code>ingress-approver</code></th>
    <td>Read/Review</td>
    <td>Ingress Approvers (Data Custodian can view)</td>
    <td>Temporary storage for files awaiting ingress approval</td>
    <td>Files are removed after approval or rejection</td>
</tr>
<tr>
    <th><code>egress-approver</code></th>
    <td>Read/Review</td>
    <td>Egress Approvers (Data Custodian can view)</td>
    <td>Temporary storage for files awaiting egress approval</td>
    <td>Files are removed after approval or rejection</td>
</tr>
</tbody>
</table><br>

<div style="border-left: 4px solid #00caef; padding-left: 12px;">
    <strong>Warning:</strong>
    Data saved outside these folders (e.g., on the VM Desktop or Documents folders) are not persistent and may be lost.
</div>

The data will only reside in the SRE during the research project. After project completion, a cost-effective, secure approach to data should be used (e.g., data should be securely archived or deleted).
