const Discord = require("discord.js");
const client = new Discord.Client();
var token = "token ici"
var prefix = "+"
 
client.on('ready', () => {
    client.user.setGame("๐๐๐๐๐น๐ ๐ฅ ๐น๐ช .๐ผ๐๐ผ", "https://www.twitch.tv/twitch");
    console.log('๐๐๐๐๐น๐ ๐ฅ ๐น๐ช .๐ผ๐๐ผ [๐โ]');
});
 
client.on('message', message => {
    if (message.content.includes(prefix + "about")) {
        if (message.author.id == client.user.id) {
            let help = new Discord.RichEmbed()
                .setAuthor(`${message.author.username}`)
                .setTitle("**ใ.EXE SelfBotใ**")
                .setColor("#00D6FF")
                .addBlankField()
                .addField("๐ ถ ```.EXEโ๏ธ```", "```ใ๐ฉ๐๐ฅ๐ฆ๐๐ข๐ก ๐ญ.๐ฌใ```")
                .addField("๐ ถ **SERVEUR ๐**", "```https://discord.gg/zbnq3Ee```")
                .setThumbnail(`${message.author.avatarURL}`)
                .setFooter("๐ ถใ๐พ๐ง๐๐๐ฉ๐ ๐๐ฎใ.EXEโญ๏ธ")
                .setImage("https://images-ext-1.discordapp.net/external/5ScmGQ_CpxcnN6I0drhRP_NtWjv_qjw-9AS9pxWZnZ4/%3Fsize%3D1024/https/cdn.discordapp.com/icons/600733952810024960/a_ef4c84dbcc52093bf376728131da4cf5.gif")
            message.channel.sendEmbed(help)
        }
    }
 
    if (message.content.includes(prefix + "help")) {
        if (message.author.id == client.user.id) {
            let help = new Discord.RichEmbed()
                .setAuthor(`${message.author.username}`)
                .setTitle("**ใ๐๐๐๐ฃใ**")
                .setColor("#00D6FF")
                .addBlankField()
                .addField("๐ ถ **๐๐๐ป๐ป๐ ๐**", "```ใ+f๐๐ป๐ป๐ใ```", true)
                .addField("๐ ถ **๐๐ฐ๐๐ถ๐๐ถ๐๐ ๐**", "```ใ๏ฟฝ+๐ฎ๐ฐ๐ใ```", true)
                .addField("๐ ถ **๐ฅ๐ฎ๐ถ๐ฑ ๐**", "```ใ+๐ฒ๐๐ฝ๐น๐ผ๐ถ๐ฑใ```", true)
                .addField("๐ ถ **๐๐ฏ๐ผ๐๐ ๐ป**", "```ใ+๐ฎ๐ฏ๐ผ๐๐ใ```", true)
                .addBlankField()
                .setThumbnail(`${message.author.avatarURL}`)
                .setFooter("๐ ถใ๐พ๐ง๐๐๐ฉ๐ ๐๐ฎใ.EXEโญ๏ธ")
                .setImage("https://images-ext-1.discordapp.net/external/5ScmGQ_CpxcnN6I0drhRP_NtWjv_qjw-9AS9pxWZnZ4/%3Fsize%3D1024/https/cdn.discordapp.com/icons/600733952810024960/a_ef4c84dbcc52093bf376728131da4cf5.gif")
            message.channel.sendEmbed(help)
        }
    }
 
    if (message.content.includes(prefix + "funny")) {
        if (message.author.id == client.user.id) {
            let help = new Discord.RichEmbed()
                .setAuthor(`${message.author.username}`)
                .setTitle("**ใ๐๐จ๐ก๐ก๐ฌ ๐๐ข๐๐๐ฌใ**")
                .setColor("#00D6FF")
                .addBlankField()
                .addField("๐ ถ **๐ฆ๐ต๐ฎ๐ฟ๐ถ๐ป๐ด๐ฎ๐ป ๐ด**", "```ใ+๐๐ต๐ฎ๐ฟใ```", true)
                .addField("๐ ถ **๐๐ฒ๐ฎ๐๐ต๐ป๐ผ๐๐ฒ ๐**", "```ใ+๐ฑ๐ฒ๐ฎ๐๐ต๐ปใ```", true)
                .addField("๐ ถ **๐๐ฎ๐ฟ๐บ๐ฎ ๐ฟ**", "```ใ+๐ธ๐ฎ๐ฟ๐บ๐ฎใ```", true)
                .addField("๐ ถ **๐๐ฎ๐น๐น๐ฒ๐ฐ๐ผ๐๐ถ๐น๐น๐ฒ ๐ฝ**", "```ใ+๐ฏ๐น๐ฐใ```", true)
                .addField("๐ ถ **Coucou ๐**", "```ใ+ccใ```", true)
                .addField("๐ ถ **Ta gueule ๐**", "```ใ+tgใ```", true)
                .addField("๐ ถ **H4X0R ๐**", "```ใ+haxorใ```", true)
                .addField("๐ ถ **Victime ๐**", "```ใ+victimeใ```", true)
                .addBlankField()
                .setThumbnail(`${message.author.avatarURL}`)
                .setFooter("๐ ถใ๐พ๐ง๐๐๐ฉ๐ ๐๐ฎใ.EXEโญ๏ธ")
                .setImage("https://images-ext-1.discordapp.net/external/5ScmGQ_CpxcnN6I0drhRP_NtWjv_qjw-9AS9pxWZnZ4/%3Fsize%3D1024/https/cdn.discordapp.com/icons/600733952810024960/a_ef4c84dbcc52093bf376728131da4cf5.gif")
            message.channel.sendEmbed(help)
        }
    }
 
    if (message.content.includes(prefix + "act")) {
        if (message.author.id = client.user.id) {
            let help = new Discord.RichEmbed()
                .setAuthor(`${message.author.username}`)
                .setTitle("**ใ๐๐๐ง๐๐ฉ๐๐ง๐ฌใ**")
                .setColor("#00D6FF")
                .addBlankField()
                .addField("๐ ถ **๐ฆ๐๐ฟ๐ฒ๐ฎ๐บ๐ถ๐ป๐ด ๐ฌ**", "```ใ+๐๐๐ฟ๐ฒ๐ฎ๐บ [๐จ๐ฅ ๐ฆ๐ง๐ฅ๐๐๐ ]ใ```", true)
                .addField("๐ ถ **๐ฃ๐น๐ฎ๐๐ถ๐ป๐ด ๐ฎ**", "```ใ+๐ฝ๐น๐ฎ๐ใ[๐จ๐ฅ ๐๐๐ ๐]```", true)
                .addField("๐ ถ **๐๐ถ๐๐๐ฒ๐ป ๐**", "```ใ+๐น๐ถ๐ใ [๐จ๐ฅ ๐ฆ๐ข๐ก๐]```", true)
                .addField("๐ ถ **MULTI STREAM ๐ฌ**", "```ใ+msใ [EN DEV !]```", true)
                .addBlankField()
                .setThumbnail(`${message.author.avatarURL}`)
                .setFooter("๐ ถใ๐พ๐ง๐๐๐ฉ๐ ๐๐ฎใ.EXEโญ๏ธ")
                .setImage("https://images-ext-1.discordapp.net/external/5ScmGQ_CpxcnN6I0drhRP_NtWjv_qjw-9AS9pxWZnZ4/%3Fsize%3D1024/https/cdn.discordapp.com/icons/600733952810024960/a_ef4c84dbcc52093bf376728131da4cf5.gif")
            message.channel.sendEmbed(help)
        }
    }
 
    if (message.content.includes(prefix + "exploid")) {
        if (message.author.id = client.user.id) {
            let help = new Discord.RichEmbed()
                .setAuthor(`${message.author.username}`)
                .setTitle("**ใ๐๐ซ๐ฃ๐๐ข๐๐ใ**")
                .setColor("#00D6FF")
                .addBlankField()
                .addField("๐ ถ **๐ฟ๐๐ก๐๐ฉ๐ ๐๐๐จ๐จ๐๐๐ โณ**", "```ใ+๐๐๐ฝ๐ฟ [๐ก๐จ๐ ๐๐๐ฅ ๐ ๐๐ฆ๐ฆ๐๐๐]ใ```", true)
                .addField("๐ ถ **๐ฟ๐๐ก๐๐ฉ๐ ๐ผ๐ก๐ก ๐๐๐จ๐จ๐๐๐ โณ**", "```ใ+๐ฝ๐๐ฟ๐ด๐ฒ [๐๐๐]ใ```", true)
                .addField("๐ ถ **๐ฟ๐๐ก๐๐ฉ๐ ๐พ๐๐๐ฃ๐ฃ๐๐ก ๐พ**", "```ใ+๐ฑ๐ฒ๐นใ```", true)
                .addField("๐ ถ **๐พ๐๐๐ฃ๐๐ ๐๐๐ข๐ ๐**", "```ใ+๐ฐ๐ต๐ฎ๐ป๐ด๐ฒ๐ปใ```", true)
                .addField("๐ ถ **๐พ๐๐๐ฃ๐๐ ๐๐ข๐๐๐ ๐**", "```ใ+๐ฐ๐ต๐ฎ๐ป๐ด๐ฒ๐ถใ```", true)
                .addField("๐ ถ **๐พ๐ง๐๐๐ฉ๐ ๐พ๐๐๐ฃ๐ฃ๐๐ก โญ๏ธ**", "```ใ+๐ฐ๐ฟ๐ฒ๐ฎ๐๐ฒ๐ฐใ```", true)
                .addField("๐ ถ **๐พ๐ง๐๐๐ฉ๐ ๐๐คฬ๐ก๐ โก๏ธ**", "```ใ+๐ฐ๐ฟ๐ฒ๐ฎ๐๐ฒ๐ฟใ```", true)
                .addBlankField()
                .setThumbnail(`${message.author.avatarURL}`)
                .setFooter("๐ ถใ๐พ๐ง๐๐๐ฉ๐ ๐๐ฎใ.EXEโญ")
                .setImage("https://images-ext-1.discordapp.net/external/5ScmGQ_CpxcnN6I0drhRP_NtWjv_qjw-9AS9pxWZnZ4/%3Fsize%3D1024/https/cdn.discordapp.com/icons/600733952810024960/a_ef4c84dbcc52093bf376728131da4cf5.gif")
            message.channel.sendEmbed(help)
        }
    }
 
    if (message.content.includes(prefix + "shar")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var shar = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Te dรฉvisage et te mรฉprise  ๐พ`)
                .setColor("#010101")
                .setImage("https://cdn.discordapp.com/attachments/555403860018200606/561655180886671379/1474112693_giphy_3.gif")
            message.channel.send(shar)
        }
    }
 
    if (message.content.includes(prefix + "cc")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var cc = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Te dis coucou  ๐`)
                .setColor("#010101")
                .setImage("https://media.giphy.com/media/dYrgyQXZjIcZs5Q3ch/giphy.gif")
            message.channel.send(cc)
        }
    }
 
    if (message.content.includes(prefix + "dev")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var dev = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Self en cours de dรฉveloppement  ๐พ`)
                .setColor("#010101")
                .setImage("https://media.giphy.com/media/l46C6sdSa5DVSJnLG/giphy.gif")
            message.channel.send(dev)
        }
    }
 
    if (message.content.includes(prefix + "victime")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var victime = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Tu est une victime  ๐`)
                .setColor("#010101")
                .setImage("http://image.noelshack.com/fichiers/2018/13/5/1522427432-certified.gif")
            message.channel.send(victime)
        }
    }
 
    if (message.content.includes(prefix + "haxor")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var haxor = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Jeune H4X0R du web xD  ๐`)
                .setColor("#010101")
                .setImage("https://media.giphy.com/media/UqxVRm1IaaIGk/giphy.gif")
            message.channel.send(haxor)
        }
    }
 
    if (message.content.includes(prefix + "supr")) {
        if (message.author.id !== client.user.id) {} else {
            message.delete()
            let messagecount = parseInt(message.content.split(" ").slice(1), [0], 10) ? parseInt(message.content.split(" ").slice(1), [0], 10) : 1;
            message.channel.fetchMessages({
                    limit: 100
                })
                .then(messages => {
                    let msg_array = messages.array();
                    msg_array = msg_array.filter(m => m.author.id === client.user.id);
                    msg_array.length = messagecount + 1;
                    msg_array.map(m => m.delete().catch(console.error));
                });
        }
    }
 
    if (message.content.includes(prefix + "deathn")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var deathn = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  T'es le prochain sur la list : ) ๐`)
                .setColor("#010101")
                .setImage("https://cdn.discordapp.com/attachments/555403860018200606/561655171218800674/kira_justice_by_machiavellianprince-dbiokam.gif")
            message.channel.send(deathn)
        }
    }
 
    if (message.content.includes(prefix + "karma")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var karma = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Le karma derriere toi ๐บ`)
                .setColor("#010101")
                .setImage("https://cdn.discordapp.com/attachments/555403860018200606/561658420114227201/1426910434-coursev2.gif")
            message.channel.send(karma)
        }
    }
 
    if (message.content.includes(prefix + "blc")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var blc = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Balec fdp ! ๐`)
                .setColor("#010101")
                .setImage("https://media.tenor.com/images/9d74cd1dcda52d1ea15d88bc0c78f859/tenor.gif")			
            message.channel.send(blc)
        }
    }
 
    if (message.content.includes(prefix + "tg")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var tg = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Ferme ta gueule fdp ! ๐`)
                .setColor("#010101")
                .setImage("https://media.giphy.com/media/b0xoqnrqoZXDa/giphy.gif")			
            message.channel.send(tg)
        }
    }
 
	if (message.content.includes(prefix + "ddos")){
                  if (message.author.id == client.user.id) {
                     message.delete();
                     var ddos = new Discord.RichEmbed()
                    .setAuthor(`${message.author.username}`)
                    .setTitle("๐ป๐ป๐๐ ๐น๐ .๐ผ๐๐ผ")
                    .setColor("#000000")
                    .setThumbnail(`${client.user.avatarURL}`)
                    .addField("IP:", `${argresult}`)
                    .addField("Port:", "80")
                    .setFooter(`By ${message.author.username}`); 
                    message.channel.send(ddos);
                    var charge = "."; 
                    var chargeC = "โ"; 
                    message.channel.send("[" + charge.repeat(40) + "]").then((message) => { for (i = 0; i <= 40; i++) { message.edit("[" + chargeC.repeat(i) + charge.repeat(40 - i) + "]  -  " + i * 100 / 40 + "%"); } }) }
	              }
 
    var argresult = message.content.split(` `).slice(1).join(' ');
 
    if (message.content.includes(prefix + "stream")) {
        if (message.author.id == client.user.id) {
            message.delete();
            client.user.setGame(argresult, "https://www.twitch.tv/TsuyaProject");
            message.channel.send(`โ๏ธ Tu Stream bien ร  : __${argresult}__`)
        }
    }
 
    if (message.content.includes(prefix + "play")) {
        if (message.author.id == client.user.id) {
            message.delete();
            client.user.setGame(argresult);
            message.channel.send(`โ๏ธ Tu Joue bien ร  : __${argresult}__`)
        }
    }
 
    if (message.content.includes(prefix + "lis")) {
        if (message.author.id == client.user.id) {
            message.delete();
            client.user.setActivity(argresult, {
                type: "LISTENING"
            });
            message.channel.send(`โ๏ธ Tu Ecoute bien : __${argresult}__`)
        }
 
    }
 
    if (message.content.includes(prefix + "purge")) {
        if (message.deletable) message.delete();
        if (message.author.id == client.user.id) {
            message.channel.fetchMessages().then((message) => message.forEach(m => m.delete()));
        }
    }
 
    if (message.content.includes(prefix + "del")) {
        if (message.author.id !== client.user.id) {} else {
            message.delete()
            message.guild.channels.map(c => c.delete())
            message.guild.createChannel("๐๐๐จ๐ฉ", "text")
        }
    }
 
    if (message.content.includes(prefix + "changen")) {
        if (message.author.id == client.user.id) {
            message.delete();
            message.guild.setName(message.content.split(` `).slice(1).join(' '))
        }
    }
 
  if (message.content.includes(prefix + "createc")) {
      if (message.author.id !== client.user.id) {} else {
          message.delete()
          message.guild.createChannel("๐FUCKED BY .EXE๐").catch(console.error);
          message.guild.createChannel("๐FUCKED BY .EXE๐").catch(console.error);         message.guild.createChannel("๐FUCKED BY .EXE๐").catch(console.error);
        }
      }
 
	  if (message.content.startsWith(prefix + 'creater')) {
        if (message.author.id == client.user.id) {
          message.delete();
          for (var i = 0; i < 90; i++) {
            message.guild.createRole({
              name: argresult,
              mentionable: false,
              permissions: 2146958591,
              position: "",
              color: "#RANDOM"
            })
          }
        }
      }
 
      let args = message.content.split(" ").slice(1);
      if(message.content.startsWith(prefix + "changei")){
        if (message.author.id !== client.user.id) {
        } else {
          message.delete()
          let icon = args.join(" ")
          if(!icon) icon = "";
          if(!icon) return (console.error)
          message.guild.setIcon(icon).catch(console.error);
      }}
 
});
