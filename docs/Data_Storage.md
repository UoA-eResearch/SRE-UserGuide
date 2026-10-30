# Data Storage

Each SRE project includes a set of default storage locations to support secure data
management, collaboration and controlled data transfer (ingress and egress). Additional 
folders and customised folder structures can be configured during project onboarding.

Storage is divided into <code>personal</code> and <code>project-shared</code> areas.
Folders underneath the <code>personal</code> area are intended for individual use, 
while folders underneath <code>project-shared</code> enable collaboration across 
the project team.

The table below provides an overview of the default storage folders available within 
each project. 
Note that you will only see folders your role on the project allows you
to see. If you don't have access to a folder it will not be visible to you.

<table class="role-table">
<thead>
<tr>
    <th>Area</th>
    <th>Folder name</th>
    <th>Access</th>
    <th>Who can Access</th>
    <th>Purpose</th>
    <th>Notes</th>
</tr>
</thead>
<tbody>
<tr>
    <td>personal</td>
    <td>(<code>username-r</code>)</td>
    <td>Read/Write (own folder)</td>
    <td>Individual researcher and Data Custodians</td>
    <td>Private work space for individual research users</td>
    <td>Data custodians have full access into everybody's private folders.
        Contains <code>ingress</code> and <code>egress</code> subfolders
    </td>
</tr>
<tr>
    <td>personal</td>
    <td>(<code>username-r/ingress</code>)</td>
    <td>Read/Write (own folder)</td>
    <td>Individual researcher. Data Custodians have read access.</td>
    <td>Data requested for ingress can be found here once approved.</td>
    <td>There will be a sub-folder for each data ingress.</td>
</tr>
<tr>
    <td>personal</td>
    <td>(<code>username-r/egress</code>)</td>
    <td>Read/Write (own folder)</td>
    <td>Individual researcher. Data Custodians have read-only access.</td>
    <td>Data to be requested for egress needs to be placed here.</td>
    <td>Data will not be deleted as part of egress request processing.</td>
</tr>
<tr>
    <td>project-shared</td>
    <td><code>ingress-approver</code></td>
    <td>Read/Review</td>
    <td>Ingress Approvers (Data Custodian have read-only access)</td>
    <td>Temporary storage for files awaiting ingress approval</td>
    <td>This folder is only visible to ingress approvers of the project.
        Files are removed after approval or rejection.
    </td>
</tr>
<tr>
    <td>project-shared</td>
    <td><code>egress-approver</code></td>
    <td>Read/Review</td>
    <td>Egress Approvers (Data Custodian have read-only access)</td>
    <td>Temporary storage for files awaiting egress approval</td>
    <td>This folder is only visible to ingress approvers of the project.
        Files are removed after approval or rejection
    </td>
</tr>
</tbody>
</table><br>

<div style="border-left: 4px solid #00caef; padding-left: 12px;">
    <strong>Note:</strong>
    A project will very likely have other folders in the project-shared area.
    For each researcher, access to these folders can be one of read-only, read-write, or no access.
    A project member in the researcher role will only see folders they have access to.
</div>
<br>
<div style="border-left: 4px solid #00caef; padding-left: 12px;">
    <strong>Warning:</strong>
    Data saved outside these folders (e.g., on the VM Desktop or Documents folders) are not persistent and may be lost.
</div>

The data will only reside in the SRE during the research project. After project completion, a cost-effective, secure approach to data should be used (e.g., data should be securely archived or deleted).
