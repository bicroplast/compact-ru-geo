Geosite и GeoIP базы вычищенные от CN, ирана, и многих иных тегов, включая adblock, но с добавлением тега **whitelist** согласно данным репозитория https://github.com/hxehex/russia-mobile-internet-whitelist<br><br>
Последние версии по ссылкам:<br>
**geoip**  https://raw.githubusercontent.com/bicroplast/compact-ru-geo/release/geoip.dat<br>
**geosite** https://raw.githubusercontent.com/bicroplast/compact-ru-geo/release/geosite.dat
##
Список тегов **geosite.dat**:<br>
https://raw.githubusercontent.com/bicroplast/compact-ru-geo/release/geosite_tags.txt
<br>
<br>В файле **geoip.dat** только теги "private" (ipv4+ipv6), "ru" (только ipv4), "telegram" (только ipv4), "whitelist" (только ipv4).<br>
В тегах ru-telegram-whitelist добавлен один ipv6 адрес-"заглушка" 2001:db8::1/128 для тех приложений, которые ругаются на пустые ipv6 списки (например Passwall2)<br>
##
Версии с добавленым тегом **ru-blocked**:<br>
https://raw.githubusercontent.com/bicroplast/compact-ru-geo/release/geosite_rublocked.dat<br>
https://raw.githubusercontent.com/bicroplast/compact-ru-geo/release/geoip_rublocked.dat
<br><br>

Версия **geoip** только ipv4 и тег **private**.<br>
https://raw.githubusercontent.com/bicroplast/compact-ru-geo/release/geoip_private.dat

