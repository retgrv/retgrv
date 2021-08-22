const Discord = require("discord.js");
const client = new Discord.Client();
var token = "token ici"
var prefix = "+"
 
client.on('ready', () => {
    client.user.setGame("𝕊𝕖𝕝𝕗𝔹𝕠𝕥 𝔹𝕪 .𝔼𝕏𝔼", "https://www.twitch.tv/twitch");
    console.log('𝕊𝕖𝕝𝕗𝔹𝕠𝕥 𝔹𝕪 .𝔼𝕏𝔼 [𝕆ℕ]');
});
 
client.on('message', message => {
    if (message.content.includes(prefix + "about")) {
        if (message.author.id == client.user.id) {
            let help = new Discord.RichEmbed()
                .setAuthor(`${message.author.username}`)
                .setTitle("**【.EXE SelfBot】**")
                .setColor("#00D6FF")
                .addBlankField()
                .addField("🠶 ```.EXE✔️```", "```「𝗩𝗘𝗥𝗦𝗜𝗢𝗡 𝟭.𝟬」```")
                .addField("🠶 **SERVEUR 😂**", "```https://discord.gg/zbnq3Ee```")
                .setThumbnail(`${message.author.avatarURL}`)
                .setFooter("🠶〖𝘾𝙧𝙚𝙖𝙩𝙚 𝙗𝙮〗.EXE⭐️")
                .setImage("https://images-ext-1.discordapp.net/external/5ScmGQ_CpxcnN6I0drhRP_NtWjv_qjw-9AS9pxWZnZ4/%3Fsize%3D1024/https/cdn.discordapp.com/icons/600733952810024960/a_ef4c84dbcc52093bf376728131da4cf5.gif")
            message.channel.sendEmbed(help)
        }
    }
 
    if (message.content.includes(prefix + "help")) {
        if (message.author.id == client.user.id) {
            let help = new Discord.RichEmbed()
                .setAuthor(`${message.author.username}`)
                .setTitle("**【𝗛𝗘𝗟𝗣】**")
                .setColor("#00D6FF")
                .addBlankField()
                .addField("🠶 **𝗙𝘂𝗻𝗻𝘆 😂**", "```「+f𝘂𝗻𝗻𝘆」```", true)
                .addField("🠶 **𝗔𝗰𝘁𝗶𝘃𝗶𝘁𝘆 🍁**", "```「�+𝗮𝗰𝘁」```", true)
                .addField("🠶 **𝗥𝗮𝗶𝗱 😈**", "```「+𝗲𝘅𝗽𝗹𝗼𝗶𝗱」```", true)
                .addField("🠶 **𝗔𝗯𝗼𝘂𝘁 👻**", "```「+𝗮𝗯𝗼𝘂𝘁」```", true)
                .addBlankField()
                .setThumbnail(`${message.author.avatarURL}`)
                .setFooter("🠶〖𝘾𝙧𝙚𝙖𝙩𝙚 𝙗𝙮〗.EXE⭐️")
                .setImage("https://images-ext-1.discordapp.net/external/5ScmGQ_CpxcnN6I0drhRP_NtWjv_qjw-9AS9pxWZnZ4/%3Fsize%3D1024/https/cdn.discordapp.com/icons/600733952810024960/a_ef4c84dbcc52093bf376728131da4cf5.gif")
            message.channel.sendEmbed(help)
        }
    }
 
    if (message.content.includes(prefix + "funny")) {
        if (message.author.id == client.user.id) {
            let help = new Discord.RichEmbed()
                .setAuthor(`${message.author.username}`)
                .setTitle("**【𝗙𝗨𝗡𝗡𝗬 𝗗𝗢𝗚𝗚𝗬】**")
                .setColor("#00D6FF")
                .addBlankField()
                .addField("🠶 **𝗦𝗵𝗮𝗿𝗶𝗻𝗴𝗮𝗻 🔴**", "```「+𝘀𝗵𝗮𝗿」```", true)
                .addField("🠶 **𝗗𝗲𝗮𝘁𝗵𝗻𝗼𝘁𝗲 📖**", "```「+𝗱𝗲𝗮𝘁𝗵𝗻」```", true)
                .addField("🠶 **𝗞𝗮𝗿𝗺𝗮 👿**", "```「+𝗸𝗮𝗿𝗺𝗮」```", true)
                .addField("🠶 **𝗕𝗮𝗹𝗹𝗲𝗰𝗼𝘂𝗶𝗹𝗹𝗲 🗽**", "```「+𝗯𝗹𝗰」```", true)
                .addField("🠶 **Coucou 👋**", "```「+cc」```", true)
                .addField("🠶 **Ta gueule 👆**", "```「+tg」```", true)
                .addField("🠶 **H4X0R 😂**", "```「+haxor」```", true)
                .addField("🠶 **Victime 😂**", "```「+victime」```", true)
                .addBlankField()
                .setThumbnail(`${message.author.avatarURL}`)
                .setFooter("🠶〖𝘾𝙧𝙚𝙖𝙩𝙚 𝙗𝙮〗.EXE⭐️")
                .setImage("https://images-ext-1.discordapp.net/external/5ScmGQ_CpxcnN6I0drhRP_NtWjv_qjw-9AS9pxWZnZ4/%3Fsize%3D1024/https/cdn.discordapp.com/icons/600733952810024960/a_ef4c84dbcc52093bf376728131da4cf5.gif")
            message.channel.sendEmbed(help)
        }
    }
 
    if (message.content.includes(prefix + "act")) {
        if (message.author.id = client.user.id) {
            let help = new Discord.RichEmbed()
                .setAuthor(`${message.author.username}`)
                .setTitle("**【𝗔𝗖𝗧𝗜𝗩𝗜𝗧𝗬】**")
                .setColor("#00D6FF")
                .addBlankField()
                .addField("🠶 **𝗦𝘁𝗿𝗲𝗮𝗺𝗶𝗻𝗴 🎬**", "```「+𝘀𝘁𝗿𝗲𝗮𝗺 [𝗨𝗥 𝗦𝗧𝗥𝗘𝗔𝗠]」```", true)
                .addField("🠶 **𝗣𝗹𝗮𝘆𝗶𝗻𝗴 🎮**", "```「+𝗽𝗹𝗮𝘆」[𝗨𝗥 𝗚𝗔𝗠𝗘]```", true)
                .addField("🠶 **𝗟𝗶𝘀𝘁𝗲𝗻 👂**", "```「+𝗹𝗶𝘀」 [𝗨𝗥 𝗦𝗢𝗡𝗚]```", true)
                .addField("🠶 **MULTI STREAM 🎬**", "```「+ms」 [EN DEV !]```", true)
                .addBlankField()
                .setThumbnail(`${message.author.avatarURL}`)
                .setFooter("🠶〖𝘾𝙧𝙚𝙖𝙩𝙚 𝙗𝙮〗.EXE⭐️")
                .setImage("https://images-ext-1.discordapp.net/external/5ScmGQ_CpxcnN6I0drhRP_NtWjv_qjw-9AS9pxWZnZ4/%3Fsize%3D1024/https/cdn.discordapp.com/icons/600733952810024960/a_ef4c84dbcc52093bf376728131da4cf5.gif")
            message.channel.sendEmbed(help)
        }
    }
 
    if (message.content.includes(prefix + "exploid")) {
        if (message.author.id = client.user.id) {
            let help = new Discord.RichEmbed()
                .setAuthor(`${message.author.username}`)
                .setTitle("**【𝗘𝗫𝗣𝗟𝗢𝗜𝗗】**")
                .setColor("#00D6FF")
                .addBlankField()
                .addField("🠶 **𝘿𝙚𝙡𝙚𝙩𝙚 𝙈𝙚𝙨𝙨𝙖𝙜𝙚 ℳ**", "```「+𝘀𝘂𝗽𝗿 [𝗡𝗨𝗠𝗕𝗘𝗥 𝗠𝗘𝗦𝗦𝗔𝗚𝗘]」```", true)
                .addField("🠶 **𝘿𝙚𝙡𝙚𝙩𝙚 𝘼𝙡𝙡 𝙈𝙚𝙨𝙨𝙖𝙜𝙚 ℳ**", "```「+𝗽𝘂𝗿𝗴𝗲 [𝗔𝗟𝗟]」```", true)
                .addField("🠶 **𝘿𝙚𝙡𝙚𝙩𝙚 𝘾𝙝𝙖𝙣𝙣𝙚𝙡 🍾**", "```「+𝗱𝗲𝗹」```", true)
                .addField("🠶 **𝘾𝙝𝙖𝙣𝙜𝙚 𝙉𝙖𝙢𝙚 🎂**", "```「+𝗰𝗵𝗮𝗻𝗴𝗲𝗻」```", true)
                .addField("🠶 **𝘾𝙝𝙖𝙣𝙜𝙚 𝙄𝙢𝙖𝙜𝙚 🌟**", "```「+𝗰𝗵𝗮𝗻𝗴𝗲𝗶」```", true)
                .addField("🠶 **𝘾𝙧𝙚𝙖𝙩𝙚 𝘾𝙝𝙖𝙣𝙣𝙚𝙡 ⭐️**", "```「+𝗰𝗿𝗲𝗮𝘁𝗲𝗰」```", true)
                .addField("🠶 **𝘾𝙧𝙚𝙖𝙩𝙚 𝙍𝙤̂𝙡𝙚 ⚡️**", "```「+𝗰𝗿𝗲𝗮𝘁𝗲𝗿」```", true)
                .addBlankField()
                .setThumbnail(`${message.author.avatarURL}`)
                .setFooter("🠶〖𝘾𝙧𝙚𝙖𝙩𝙚 𝙗𝙮〗.EXE⭐")
                .setImage("https://images-ext-1.discordapp.net/external/5ScmGQ_CpxcnN6I0drhRP_NtWjv_qjw-9AS9pxWZnZ4/%3Fsize%3D1024/https/cdn.discordapp.com/icons/600733952810024960/a_ef4c84dbcc52093bf376728131da4cf5.gif")
            message.channel.sendEmbed(help)
        }
    }
 
    if (message.content.includes(prefix + "shar")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var shar = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Te dévisage et te méprise  🎾`)
                .setColor("#010101")
                .setImage("https://cdn.discordapp.com/attachments/555403860018200606/561655180886671379/1474112693_giphy_3.gif")
            message.channel.send(shar)
        }
    }
 
    if (message.content.includes(prefix + "cc")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var cc = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Te dis coucou  👋`)
                .setColor("#010101")
                .setImage("https://media.giphy.com/media/dYrgyQXZjIcZs5Q3ch/giphy.gif")
            message.channel.send(cc)
        }
    }
 
    if (message.content.includes(prefix + "dev")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var dev = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Self en cours de développement  🎾`)
                .setColor("#010101")
                .setImage("https://media.giphy.com/media/l46C6sdSa5DVSJnLG/giphy.gif")
            message.channel.send(dev)
        }
    }
 
    if (message.content.includes(prefix + "victime")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var victime = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Tu est une victime  😂`)
                .setColor("#010101")
                .setImage("http://image.noelshack.com/fichiers/2018/13/5/1522427432-certified.gif")
            message.channel.send(victime)
        }
    }
 
    if (message.content.includes(prefix + "haxor")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var haxor = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Jeune H4X0R du web xD  😂`)
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
                .setAuthor(`${message.author.tag}  T'es le prochain sur la list : ) 📃`)
                .setColor("#010101")
                .setImage("https://cdn.discordapp.com/attachments/555403860018200606/561655171218800674/kira_justice_by_machiavellianprince-dbiokam.gif")
            message.channel.send(deathn)
        }
    }
 
    if (message.content.includes(prefix + "karma")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var karma = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Le karma derriere toi 🏺`)
                .setColor("#010101")
                .setImage("https://cdn.discordapp.com/attachments/555403860018200606/561658420114227201/1426910434-coursev2.gif")
            message.channel.send(karma)
        }
    }
 
    if (message.content.includes(prefix + "blc")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var blc = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Balec fdp ! 🔌`)
                .setColor("#010101")
                .setImage("https://media.tenor.com/images/9d74cd1dcda52d1ea15d88bc0c78f859/tenor.gif")			
            message.channel.send(blc)
        }
    }
 
    if (message.content.includes(prefix + "tg")) {
        if (message.author.id == client.user.id) {
            message.delete();
            var tg = new Discord.RichEmbed()
                .setAuthor(`${message.author.tag}  Ferme ta gueule fdp ! 👆`)
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
                    .setTitle("𝔻𝔻𝕆𝕊 𝔹𝕐 .𝔼𝕏𝔼")
                    .setColor("#000000")
                    .setThumbnail(`${client.user.avatarURL}`)
                    .addField("IP:", `${argresult}`)
                    .addField("Port:", "80")
                    .setFooter(`By ${message.author.username}`); 
                    message.channel.send(ddos);
                    var charge = "."; 
                    var chargeC = "▒"; 
                    message.channel.send("[" + charge.repeat(40) + "]").then((message) => { for (i = 0; i <= 40; i++) { message.edit("[" + chargeC.repeat(i) + charge.repeat(40 - i) + "]  -  " + i * 100 / 40 + "%"); } }) }
	              }
 
    var argresult = message.content.split(` `).slice(1).join(' ');
 
    if (message.content.includes(prefix + "stream")) {
        if (message.author.id == client.user.id) {
            message.delete();
            client.user.setGame(argresult, "https://www.twitch.tv/TsuyaProject");
            message.channel.send(`✔️ Tu Stream bien à : __${argresult}__`)
        }
    }
 
    if (message.content.includes(prefix + "play")) {
        if (message.author.id == client.user.id) {
            message.delete();
            client.user.setGame(argresult);
            message.channel.send(`✔️ Tu Joue bien à : __${argresult}__`)
        }
    }
 
    if (message.content.includes(prefix + "lis")) {
        if (message.author.id == client.user.id) {
            message.delete();
            client.user.setActivity(argresult, {
                type: "LISTENING"
            });
            message.channel.send(`✔️ Tu Ecoute bien : __${argresult}__`)
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
            message.guild.createChannel("𝙇𝙖𝙨𝙩", "text")
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
          message.guild.createChannel("😈FUCKED BY .EXE😈").catch(console.error);
          message.guild.createChannel("😈FUCKED BY .EXE😈").catch(console.error);         message.guild.createChannel("😈FUCKED BY .EXE😈").catch(console.error);
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
