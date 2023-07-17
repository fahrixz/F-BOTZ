let fs = require('fs')
let handler = async (m, { conn, args, command }) => {
let thum = 'https://telegra.ph/file/33bca7ae34a3bceb7f954.png'
let reel =
`
┏━━━ꕥ〔 *${global.wm2}* 〕ꕥ━⬣ 
┃Dana: [ CHAT OWNER ] ✅️
┃Pulsa XL: [081977815539 
┃Pulsa: - 
┃Gopay: [ CHAT OWNER ] ✅️
┗━━━ꕥ
┏━━━ꕥ〔 *Website* 〕ꕥ━⬣ 
┃Saweria: https://saweria.co/myukonet
┃Thanks for Donationing!
┗━━━ꕥ
`
 await conn.sendFile(m.chat, thum, 'thumb.jpg', `${reel}`, m)
}

handler.help = ['donasi']
handler.tags = ['info', 'main']
handler.command = /^(donasi|donate)$/i
module.exports = handler