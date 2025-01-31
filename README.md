# Roblosec-Data-Base
Database with collection of robloxsecurity cookies stored on flask. 

**How it works:**
Instead of directly sending tokens to a webhook, and the fear of being reversed engineered and your server nuked, it send a request to a flask server. The flask server requires a special key to access, so once the malware is ran there is nothing you can do about it.

**Anti AV**
The whole point of using another server is so it is not detected by anti viruses and sites like uncoverit.org
