Fivem泄露网www.vag.gg
# Fivem插件-OKOK通知插件
# 插件使用教程
--列子：
exports['okokNotify']:Alert("Title", "Message", Time, 'type')
这个写在client.lua里

--列子：
TriggerClientEvent('okokNotify:Alert', source, "Title", "Message", Time, 'type')
这个写在server.lua里

--列子：
exports['okokNotify']:Alert("提醒", "更换此地文字", 5000, 'info')

--列子：
TriggerClientEvent('okokNotify:Alert', source, "提醒", "更换此地文字", 5000, 'info')

--列子：
TriggerClientEvent('okokNotify:Alert', _source, "提醒", "更换此地legacy文字", 5000, 'info')


--提示颜色更换: 

success (成功绿色) - info (信息蓝色) - warning (警告黄色) - error (错误红色) - phone (电话橙色) - neutral (中性灰色)
