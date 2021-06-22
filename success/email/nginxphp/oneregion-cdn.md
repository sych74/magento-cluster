**Magento environment**: [${globals.PROTOCOL}://${env.domain}/](${globals.PROTOCOL}://${env.domain}/)

**CDN Endpoint URL**:  [${globals.CDN_URL}](${globals.CDN_URL})

Use the following credentials to access the admin panel:

**Admin Panel**: [${globals.PROTOCOL}://${env.domain}/admin/](${globals.PROTOCOL}://${env.domain}/admin/)  
**Login**: admin  
**Password**: ${globals.MG_ADMIN_PASS}  

Manage the database nodes using the next credentials:

**phpMyAdmin Panel**: [https://node${nodes.sqldb.master.id}-${env.domain}/](https://node${nodes.sqldb.master.id}-${env.domain}/)  
**Username**: ${globals.DB_USER}    
**Password**: ${globals.DB_PASS}  
