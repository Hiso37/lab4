Практична робота №4
Тема: Мережі та інтернет на практиці

Частина 1: traceroute і ping до реальних серверів

Ping:
<img width="598" height="566" alt="{8DD63E26-5D70-4E6A-8C86-41DE1F4DF19E}" src="https://github.com/user-attachments/assets/bee1677c-9cc7-41f7-b0fd-c5b9a8a321e8" />

Traceroute:
<img width="568" height="395" alt="{FF393DBF-C6ED-463A-A821-69E805CC3DA8}" src="https://github.com/user-attachments/assets/10ec1b58-b1f9-44ae-9f59-39dd7c847ad6" />
<img width="534" height="336" alt="{225BA6FE-533B-41DB-8B9F-24BF0C312089}" src="https://github.com/user-attachments/assets/2af1852e-3475-45eb-b2f4-0aaede4f3cbd" />


Ping до digi24.ro не повернув відповідей, оскільки сервер блокує ICMP; traceroute показав 11 видимих хопів до фільтра. 
Ping до japantimes.co.jp середній час 64 мс, але його адреса належить Cloudflare, тож відповідав найближчий вузол, а не сервер у Японії. 
Затримка до далекого сервера більша через фізичну відстань і кількість маршрутизаторів, тому оптимізацією коду її не прибрати.

Частина 2: curl -v і TLS-хендшейк
<img width="1097" height="122" alt="image" src="https://github.com/user-attachments/assets/5668cdf3-2a9d-41d4-8031-c4a173167fb4" />
<img width="916" height="444" alt="{DC88DDBF-34B4-49DC-A1D6-CE037C2E8863}" src="https://github.com/user-attachments/assets/bdbc9cb6-9c16-4628-88c7-413390db4dbd" />

Частина 3: Base64 проти SHA-256
<img width="628" height="175" alt="{B1A95976-B5B8-4492-8489-C1BBDBC6480F}" src="https://github.com/user-attachments/assets/e6468f53-4471-4518-b984-5956230bbe25" />
