
#3 🎨 Logo Maker ##

@pbot.on_message(filters.command("logo"))
async def make_logo(_, message):
    imgcaption = f"""

☘️ Logo Created Successfully
◇───────────────◇
🔥 Created by : @devid999_bot
🌷 Requestor : {message.from_user.mention}
⚡️ Powered By   : @devid_helper
◇───────────────◇
"""
    if len(message.command) < 2:
            return await message.reply_text("Please give a text to make logo 📸")
    m = await message.reply_text("📸 Creating..")
    text = message.text.split(None, 1)[1]
    photo = get(f"https://api.single-developers.software/logohq?name={text}").history[1].url
    await m.edit("📤 Uploading ...")
    await pbot.send_photo(message.chat.id, photo=photo, caption=imgcaption.format(message.from_user.mention),
                 reply_markup=InlineKeyboardMarkup(
            [
                [
                    InlineKeyboardButton(
                        "••Telegraph Link••", url=f"{photo}"
                    

## deploy to heroku ##
<a href="https://heroku.com/deploy?template=https://github.com/chathush999/Image-Tool">
            <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">

