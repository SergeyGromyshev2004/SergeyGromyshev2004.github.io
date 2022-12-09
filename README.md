# SergeyGromyshev2004.github.io![images](https://user-images.githubusercontent.com/114712725/206611744-f9ba7575-41f1-4c99-988e-e834ef7ad040.jpg)
![images](https://user-images.githubusercontent.com/114712725/206611751-ba108284-9d4d-4423-bef2-7553ad31d8b1.jpg)

<!--Dayspedia.com widget--><iframe width='273' height='388' style='padding:0!important;margin:0!important;border:none!important;background:none!important;background:transparent!important' marginheight='0' marginwidth='0' frameborder='0' scrolling='no' comment='/*defined*/' src='https://dayspedia.com/if/analog/?v=1&iframe=eyJ3LTExIjp0cnVlLCJ3LTEzIjp0cnVlLCJ3LTE1Ijp0cnVlLCJ3LTExMCI6dHJ1ZSwidy13aWR0aC0wIjp0cnVlLCJ3LXdpZHRoLTEiOmZhbHNlLCJ3LXdpZHRoLTIiOmZhbHNlLCJ3LTE2IjoiNDhweCIsInctMTciOiIxNiIsInctMjEiOnRydWUsImJnaW1hZ2UiOjIsImJnaW1hZ2VTZXQiOnRydWUsInctMjFjMCI6IiNiNDA0MDQiLCJ3LTAiOnRydWUsInctMyI6dHJ1ZSwidy0zYzAiOiIjMzQzNDM0Iiwidy0zYjAiOiIxIiwidy0yMCI6dHJ1ZSwidy00IjoiIzAwN2RiZiIsInctMTgiOnRydWUsInctd2lkdGgtMmMtMCI6IjMwMCIsInctMTE1IjpmYWxzZSwidy0yMyI6dHJ1ZSwidy0yM2MwIjoiI2U3NWEwZCIsInctMjYiOmZhbHNlLCJ3LTI2YjAiOiIxIiwidy0yNyI6dHJ1ZSwidy0yN2MwIjoiIzM0MzQzNCIsInctMjQiOiIjMzQzNDM0Iiwidy0xM2MwIjoiI2ZmMDA1MSIsInctMjIiOiIjMzQzNDM0Iiwidy0yNSI6IjE2MCJ9&lang=ru&cityid=5720'></iframe><!--Dayspedia.com widget ENDS-->

$$\ce{3C^2-H2=C^2-H2 + 2KMn^+^7O4 + 4H2O = 2KOH + 2Mn^+^4O2 + 3C^-H2(OH) - C^-H2(OH)}$$

$$\\ \ce{Mn^+^7 + 3\overline{e} \longrightarrow  Mn^+^4 |2}$$

$$\\ \ce{6}$$

$$\\ \ce{2C^2- - 2\overline{e} \longrightarrow 2C^- |3}$$

# Viktorina.py
import random
a=['8', '2']
b=['8', '2']
h=0
print("Введите ответ")
while len(a)>0:
    s=random.randint(0,len(a)-1)
    print(a[s])
    if input()==b[s]:
        a.pop(s)
        b.pop(s)
    else:
        h+=1
print(f'количество ошибок: {h}')
