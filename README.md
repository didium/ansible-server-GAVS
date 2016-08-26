# ansible-server-GAVS

<h3>Configure and Install programs on other Linux PCs within/outside an organization using Ansible. </h3></br>

<b>Changes to be done at Source Machine: Ansible Hosts</b></br>

Add this line to hosts file at /etc/ansible/hosts (Ignore the " ")

<code>
"Replace with your IP" ansible_ssh_pass="Replace with your System password" ansible_ssh_user="Replace with your System username"
</code>

</br>Add more IP information in this format, for configuring mutilple servers

</br><b>Changes to be done at Target machine:</b></br>
1. Install Ansible</br>
2. Install openssh-server</br>
3. Change Sudoers by typing </br><code> sudo visudo </code>

</br>And add this line at end of the document
</br>"user" ALL = (ALL) NOPASSWD:ALL

<b> -- Dibin Dixit </b>
