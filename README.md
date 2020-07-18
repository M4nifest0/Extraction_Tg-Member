# ![Locations](https://github.com/attakercyebr/haxk4lx_toolkit/blob/master/levlogo.png) 

**********************************************************

# Extraction_Tg-Member

# <center>![Locations](https://github.com/attakercyebr/hack4lx_IPTV/blob/master/83837757_2519460388336847_1590182160688480256_n.jpg) </center>

**********************************************************

**This tool is a Proof of Concept and is for Educational Purposes Only,Extraction_Tg-Member shows what data a malicious website can gather about you and your devices and why you should not click on random links and allow critical permissions such as Location etc.**

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

⚠️  Read-First:

🔞 The author of the does not encourage anyone to repeat this. Otherwise, you will be solely responsible. The was created for informational purposes. And for the fact that you caution you!🙏

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

  Description 👀 Extraction_Tg-Member

  Title 📌Extract a member from Telegram | Thanks Please introduce our channel to other friends

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●


def printlogo():

    pc.printout(" _                _    _  _   _        \n", pc.YELLOW)     
    pc.printout("| |__   __ _  ___| | _| || | | |_  __  \n", pc.YELLOW)
    pc.printout("| '_ \ / _` |/ __| |/ / || |_| \ \/ /  \n", pc.YELLOW)
    pc.printout("| | | | (_| | (__|   <|__   _| |>  <   \n", pc.YELLOW)
    pc.printout("|_| |_|\__,_|\___|_|\_\  |_| |_/_/\_\  \n", pc.YELLOW)
                                     
    print('\n')
    pc.printout("Version 1.0 - Developed by hack4lx | ʍ4ղíƒҽՏԵ0 ϲվҍҽɾ ՏҽϲմɾíԵվ Եҽɑʍ™ | - 2020\n\n", pc.YELLOW)
    pc.printout("Type 'list' to show all allowed commands\n")
    pc.printout("Type 'FILE=y' to save results to files like '<target username>_<command>.txt (deafult is disabled)'\n")
    pc.printout("Type 'FILE=n' to disable saving to files'\n")                                                                               
                                                                                      
✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

    First you need create app on https://my.telegram.org 
    api_id = hack4lx
    api_hash = 'hack4lx'
    phone = '+hack4lx'
    limit = 100

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

    def get_chat_info(username, client):
    try:
        chat = client(ResolveUsernameRequest(username))
    except UsernameNotOccupiedError:
        print('Chat/channel not found!')
        sys.exit()
    result = {
        'chat_id': chat.peer.channel_id,
        'access_hash': chat.chats[0].access_hash
    }
    return result


    def dump_users(chat, client):
    counter = 0
    offset = 0
    chat_object = InputChannel(chat['chat_id'], chat['access_hash'])
    all_participants = []
    print('Process...')
    while True:
        participants = client.invoke(GetParticipantsRequest(
                    chat_object, ChannelParticipantsSearch(''), offset, limit
                ))
        if not participants.users:
            break
        all_participants.extend(['{} {}'.format(x.id, x.username)
                           for x in participants.users])
        users_count = len(participants.users)
        offset += users_count
        counter += users_count
        print('{} users collected'.format(counter))
        sleep(2)
    with open('users.txt', 'w') as file:
        file.write('\n'.join(map(str, all_participants)))

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●


💀 Made by ☠️👊 𝕿𝖍𝖎𝖘 𝕴𝖘 𝕿𝖍𝖊 𝓜4𝓷𝓲𝓯𝓮𝓼𝓽0 𝕿𝖊𝖆𝖒™💪🏴‍☠️

  Author 🏴‍☠️ hack4lx

  Aate ♾ 2020 July

  Version 👁‍🗨 1.0.0

 Usage 👌 https://my.telegram.org/auth | python3 


 Channel  Combo List 👍  [![Telegram Chanel](https://img.shields.io/badge/chat%20on-Telegram-blue.svg)](https://t.me/hack4lxCombo)


✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

☠️👊𝓷𝓲𝓯𝓮𝓼𝓽4𝓷𝓲𝓯𝓮𝓼𝓽0 (MCS) Telegram Groups We are a team of  𝓑𝓵𝓪𝓬𝓴  𝓗𝓪𝓽  𝓗𝓪𝓬𝓴𝓮𝓻𝓼  because we know what is at stake. We prepare hackers by providing training and hacking tools. We are one of the few Black hat hacking teams that show you their skills.👁‍🗨💪

👇🏾👇🏾👇🏾👇🏾👇🏾

[![Join To Telegram Groups](https://img.shields.io/badge/chat%20on-Telegram-blue.svg)](https://t.me/M4nifest0)

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

Telegram Chat ID 📞 [![Telegram Chat](https://img.shields.io/badge/chat%20on-Telegram-blue.svg)](https://t.me/hack4lx)

✂️●●●●●●●●●●●●●●●●●●●●●●●●●●●●

<p align="center">
  ✯ Follow Me On ♥️👇🏾👇🏾👇🏾
</p>
<p align="center">
  <a href="https://www.youtube.com/channel/UC73xXDVwfS8mE4ExtOg63sw/videos?view_as=subscriber">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQIe0KA-4U2wilfj3CwcetOZYjaXr_C6bh5b9Xp3eDfeATwkhn82b70ELBt&s" width="40" height="40">
  </a>
  <a href="https://t.me/M4nifest0">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRnOo5m2bMLsKVd9-ZjGf0xl0SAVqj9Fgxvu89_iu24qUcWQJ-X_1lvI5yOIA&s" width="40" height="40">
</p>


