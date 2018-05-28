###  Backups

<dl>
    <dt>Approach</dt>
    <dd class="fragment">Daily DB backup via cron</dd>
    <dd class="fragment"><a href="https://engineering.growella.com/automatic-database-backups-amazon-s3/">Push to lifecycle'd S3 bucket via <code>s3cmd</code></a></dd>
    <dt class="fragment">Alternatives</dt>
    <dd class="fragment"><a href="https://shareasale.com/r.c class="fragment"fm?b=948660&u=1518741&m=68863&urllink=&afftrack=">Backup Buddy</a></dd>
    <dd class="fragment"><a href="https://blogvault.net?src=69AB53">BlogVault</a></dd>
    <dd class="fragment"><a href="https://vaultpress.com/">VaultPress</a></dd>
</dl>

Note:

* Performing backups if you control the system isn't difficult
* Find a backup schedule that fits your needs
* Also ran Digital Ocean snapshots weekly
