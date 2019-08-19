# TelegramGroupMembersExport


api_id = 699533

api_hash = '2a9773c60013f39be69700eb49de3b04'

phone = '+91**********'

client = TelegramClient(phone, api_id, api_hash)


The above code block serves as the permission for the number in masked(*) to use the telegram API to export the channel list.
The CSV file will contain the member id and username. 
There can be scenario where the member will not have a username in that case the member name field will be kept blank.

