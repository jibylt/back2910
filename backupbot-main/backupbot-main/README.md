# backupbot

## TODO
<.env>  
1行目:自分のbotのTOKENを割り当て  
  
<config.json>  
2行目:admin_list内にbot管理者にしたいアカウントのidを配列型で記入  
  
<index.js>  
53行目:起動ログを流すchのidを記入  
76行目:botのidを記入  
77行目:botのsecretを記入  
78行目:https://${プロジェクト名}.glitch.me/callbackと記入  
  
<verify.js>  
53行目:urlに${生成したoauth2Link}&state=${BigInt(interaction.guild.id).toString(16).toUpperCase()}-${BigInt(role.id).toString(16).toUpperCase()}を代入
