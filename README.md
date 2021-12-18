## FormAPI Fix to support pocketmine 4.0.0

Simple API for creating forms for MCPE clients (PocketMine 4.0.x only)<br />
เป็น API สำหรับสร้าง form เมนู สำหรับ pocketmine 4.0.x เท่านั้น

I edited from jojoe77777 for it to support pocketmine 4.0.x <br />
ผมทำการแก้ไขจากของคุณ jojoe77777 เพื่อให้มันใช้งานกับ pocketmine 4.0.x ได้

It is Free To use!<br />
มันใช้งานฟรี!

code to call FormAPI Fix to Pocketmine 4.0.0 <br />
change form FormAPI
'''
$formapi = $this->plugin->getServer()->getPluginManager()->getPlugin("FormAPI");
'''
to
'''
$formapi = $this->plugin->getServer()->getPluginManager()->getPlugin("FormAPIFix");
'''
image preview<br />
ภาพตัวอย่าง
![Google ](https://i.imgur.com/2zMvLud.png)

![Googlez ](https://i.imgur.com/3uxEYHF.png)
