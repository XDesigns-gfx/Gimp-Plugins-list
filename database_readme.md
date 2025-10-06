
🧮 How the Hash Was Computed
Each hash =
sha256("https://github.com/{owner}/{name}")

Example in Python:

``` python

import hashlib

url = "https://github.com/kamilburda/batcher"
hash = hashlib.sha256(url.encode()).hexdigest()
print(hash)


```

Now we can fast check if needed using known_hashes.txt
