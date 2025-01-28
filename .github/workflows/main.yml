const fs = require('fs');
if (fs.existsSync('config.env')) require('dotenv').config({ path: './config.env' });

function convertToBool(text, fault = 'true') {
    return text === fault ? true : false;
}

module.exports = {
    SESSION_ID: process.env.SESSION_ID || "BWM-XMD;;;H4sIAAAAAAAAA61VaW+rOBT9L/6adAIBAkSqNA4kIdAsTchCRqORA2YNm21CyFP/+4imVSu9rSMNnyxjn3vuvecefwNZHlFs4QYMv4GCRBfEcLtkTYHBEIwq38cEdIGHGAJDgPRK1SUS27Hk1mkSzdVkr4lTuWPvLwmc3SZbikIIbc54fgQvXVBUp3Pk/gLwhDKzEAIyMhdVdtCeIPacJTxphTEqb+ZciNUzP0n90d6Aj+ClRUQRibJgXIQ4xQSdLdysUES+Rl+zgtvqZHlutVqhqZyVl+31YIi+mdPewj42cLHXp6bs+7vga/StVb02O9eyJ2irGxVFFqRmL/esc8BrAZcuwl0cLRdRj27EO30aBRn2Zh7OWMSaL9e91E67mtqHgyUUMxP34fmQzSWkK9zcGx9O3nSeXpbh1hMS7mvEZ6Nsxo7LKlSmPCkVJVBS05fCcjHnLx2Zllo1WS4EixMS5zPxFXnXSvJf6p6sGOfQSbK+PVnXjnRi+UAb7zkYzyYQoU6+MlFHnDXpdJd/jf6WjPtTzrfy587UYsetlvYd12nyJXXXz0tfShtXI7J7msHnD/qIVeRXLHV/v502uTsfsL2JxGW2DhwnNwiHDHshE26zj9xme9NXhhXYvqPrhj8peg3TZarBeneRzGMQ5xsaGJUscp0j5XbbIHh8zSjBzcwDQ/6lCwgOIsoIYlGeve4pfBcg77LBLsHstbyAp95coHyZOdVaGcgS5gTJGDXlzN1gcTU13R0rkZ8TUgaPoAsKkruYUuwZEWU5aeaYUhRgCoZ/vXaqTZrgNGfYjDwwBH1JlAfKQBFEQfmT/lGHiFFUFH9kmIEu8EmezjEYMlLhLni9IKuK1Fd1TRcHUFUVURWFiSaOeZUXdJ6H/TbF9B7UjlJMGUoLMORlQeEGUl+UXrr/Dw++P4YKz0v8WBbUyWAijCaKIk8mkqQr+kgSfsvj7y7I8JXdddxWX+C7wI8IZdusKs458t5F/v4TuW5eZWzTZK7WLjABw0/bmLEoC2ibWZUh4obRBWttHmDoozPFL13g4Uvk4hYPRPo/VVzt7HVgFYNaCGBZ1yJsOxjm2f2I0vcxloTTA+di9UFU8ekBqbzwIPi+IA5cNFCFAWjLcbeQ9s5PFR1YN7lpQiePr9upKtrHp/5SzzviUr37212KmGDvvcon5CZVYecJzn6By9WZNV9Bp94878NFEqCmHu+zvMF7+An3LnEw/PZh21rutXiytZvb6nEF2m61cb5Tw1D4Xg8Zag8DynI3aaO8taC972GGojNtLX5mwcQWn28OiS/QcWADoQVhOyXvLXu3gvuomQq/CJWyEvarqe8ZyjiDp/6uv0oOuuIJdB/Xi96mf71oyQ9B2o7lcTw5LhZhXfIa2uyIrruD8xzPJX/DM9O21GS5XI/FmX3mPeVppCczmjTkKbCI7CMVRe5ACVA1njrR7rRc2IdiTEbwsY12l87nYCoMuC0NiZaXshQcC9/L9dq43piRHBeuYuexIUdhMg/9Ri83PYn41hPPHfRB6cJjtolVXnxit/CwUcKaOYfCQVUVvpnUq0me3x6n6M0+7kLzI/zq9W89+F2rPiTPvXQ/Qbw9Hj+R1WjjL2zHtwjj42smrHsjs56qZy+WJnXP8ORJrug+x+ipLiB4aWe5OCPm5yRtZZGeEOiCM6IMfozsj1yg3wVpA4tiwxB7n3QA20/TN+DlX1MV36oUCQAA",
    CAPTION: process.env.CAPTION || "*ᴘᴏᴡᴅᴇʀᴇᴅ ʙʏ ᴛᴀʟᴋᴅʀᴏᴠᴇ*",
    ALWAYS_ONLINE: process.env.ALWAYS_ONLINE || "true",
    AUTO_READ_STATUS: process.env.AUTO_READ_STATUS || "true",
    READ_MESSAGE: process.env.READ_MESSAGE || "false", // Added auto-read configuration
    AUTO_TYPING: process.env.AUTO_TYPING || "true",
    CURRENT_STATUS: process.env.CURRENT_STATUS || "false",
    MODE: process.env.MODE || "public",
    AUTO_VOICE: process.env.AUTO_VOICE || "false",
    AUTO_STICKER: process.env.AUTO_STICKER || "false",
    AUTO_REPLY: process.env.AUTO_REPLY || "false",
    ALIVE_IMG: process.env.ALIVE_IMG || "https://i.imgur.com/UfzyhWN.jpeg",
    ALIVE_MSG: process.env.ALIVE_MSG || "HII DEAR IM ONLINE I'M BYTE-LITE WHATSAPP BOT 😊♻️",
    ANTI_LINK: process.env.ANTI_LINK || "true",
    ANTI_BAD: process.env.ANTI_BAD || "true",
    PREFIX: process.env.PREFIX || ".",
    FAKE_RECORDING: process.env.FAKE_RECORDING || "false",
    AUTO_REACT: process.env.AUTO_REACT || "true",
    HEART_REACT: process.env.HEART_REACT || "false",
    OWNER_REACT: process.env.OWNER_REACT || "false",
    BOT_NAME: process.env.BOT_NAME || "ʙʏᴛᴇ-ʟɪᴛᴇ",
    AUTO_STATUS_REPLY: process.env.AUTO_STATUS_REPLY || "true",
    AUTO_STATUS__MSG: process.env.AUTO_STATUS__MSG || "`𝒚𝒐𝒖𝒓 𝒔𝒕𝒂𝒕𝒖𝒔 𝒔𝒆𝒆𝒏 𝒋𝒖𝒔𝒕 𝒏𝒐𝒘 𝒃𝒚 𝒃𝒚𝒕𝒆-𝒍𝒊𝒕𝒆`",
    OMDB_API_KEY: process.env.OMDB_API_KEY || "76cb7f39", // omdbapi.com
};
