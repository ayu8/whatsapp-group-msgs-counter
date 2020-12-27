# Whatsapp Group Msgs Counter

This simple python script counts the number of messages sent by all the participants in a Whatsapp group and shows them in descending order (Maximum to Minimum).

Chat data exported from the Whatsapp group (in text format) is taken as the input. Phone numbers of all active members are extracted and stored in a list. The script also returns the name of the contact who sent the most number of messages to the group as "XYZ is the spammer in the group with ___ msgs."

Note: Script does not count stickers as messages. This is because exported whatsapp chat does not include stickers.

# How to obtain exported chat data in text format

In your whatsapp, Go to Settings > Chats > Chat History > Export Chat > Choose a chat (Group) > Send to someone so that you can download that in your system.

This is a modified version of another Chat Counter, to check that, [click here](https://github.com/sharmadeepesh/whatsapp-message-counter)
