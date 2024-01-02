- 👋 Hi, I’m @asimalperen
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
asimalperen/asimalperen is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import requests

def test_http_status_code():
    response = requests.get("https://flights-api.buraky.workers.dev/")
    assert response.status_code == 200
