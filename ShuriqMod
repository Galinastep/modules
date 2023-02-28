from .. import loader, utils 
import asyncio

class ModuleMod(loader.Module): 
  "Описание" 
  strings = {"name": "ShuriqMod"} 

  async def шурикcmd(self, message): 
    """Чекает жертву реплаем на ид ириса""" 
    reply = await message.get_reply_message()
    a = reply.text
    for i in a.splitlines():
      try:
        b = [x for x in i.split('@')]
        await message.respond("Шурик з @" + b[1])
        await asyncio.sleep(0.5)
      except:
        pass
        await message.delete()
