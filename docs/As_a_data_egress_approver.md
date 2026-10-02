# As a Data Egress Approver

As an Egress Approver, use Data Egress Requests to check and approve files(s) that a Researcher wants to export from the project environment. 

## View egress requests 

<ol>
  <li>
    You will receive an email informing you of an Egress Request to approve.
  </li>
  <li>
    Log in to the SRE and, if needed, change to the <strong>Egress Approver</strong> role.
  </li>
  <li>
    Select <strong>Data Egress Requests</strong> from the left-hand project menu on the Project Dashboard.
  </li>
</ol>

<figure markdown>
  ![egress_approver_1](img/egress_approver_1.png)
  <figcaption> </figcaption>
</figure>

<ol start="4">
  <li>
    Use the <strong>Management VM</strong> to view and inspect the file(s).
    <ul>
      <li>
        <strong>Windows VM:</strong> Click on the File Explorer from the taskbar at the bottom of the virtual desktop. Select <strong>This PC</strong> to display available folders within "Network locations". Select <code>project_shared</code> > <code>ingress-approver</code> > <code>username-r</code> (user who made the request).
      </li>
      <li>
        <strong>Linux VM:</strong> Click on the <strong>File Manager</strong> from the taskbar at the bottom of the virtual desktop. Select <code>project_shared</code> > <code>egress-approver</code> > <code>username-r</code> (user who made the request).
      </li>
    </ul>
  </li>
</ol>

## Approve or decline a request 

<ol start="5">
  <li>
    Return to <strong>Data Egress Requests</strong> on the Project Dashboard.
  </li>
  <li>
    <strong>Approve</strong> or <strong>Reject</strong> the egress request.
    <div class="callout">
      The request State in <strong>Egress request history</strong> will change from <em>pending_approval</em> to <em>completed</em>. The files will be automatically deleted from the staging area following approval or rejection.
    </div>
  </li>
</ol>
Please get in touch with the researcher if the request is rejected and provide them with advice for the next steps.

<figure markdown>
  ![egress_approver_2](img/egress_approver_2.png)
  <figcaption> </figcaption>
</figure>