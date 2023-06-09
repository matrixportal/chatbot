# chatbot
Bu proje basit bir Chatbot projesidir. Projenin gelişimine katkı sağlayabilir veya klonlayabilirsiniz. Kurulum adımlarını takip ederek kolayca çalıştırabilirsiniz. 

Bağımlılıklar:
- numpy-1.24.3
- torch-2.0.1
- nltk-3.8.1
- requests-2.30.0
- pytz-2023.3

KURULUM!
Sanal alan oluşturma:
Tercihen conda ile bir sanal alan oluşturabilirsiniz:.

````bash
conda create -n chatbot python=3.8
conda activate chatbot
````
Aşağıdaki komutlarla repoyu klonlayın, bağımlılıkları yükleyin ve  model verillerini yükleyin.
````bash
git clone https://github.com/matrixportal/chatbot.git
cd chatbot
pip install -r requirements.txt
python train.py
````
Chatbotla komut satırında sohbet etmek için aşağıdaki komutu kullanabilirsiniz:
````bash
python chatbot.py
````

Web sayfasındaki sobet arayüzüne ulaşmak için önce tek seferliğine aşağıdaki komutla modejs modüllerini yükleyin:
````bash
npm i
````
Artık istediğiniz zaman sadece aşağıdaki komutu kullanarak Chatbot'u  başlatabilirsiniz:
````bash
node chatbot.js
````

Chatbotla sohbete başlamak için http://localhost:5000/ adresini tarayıcıda açın:


Veritabanı oluşturma:
intents.txt dosyası chatbot'un veritabanı intents.json dosyasını hazırlamayı kolaylaştırmak için örnekteki  gibi bir intents.txt dosyasını cep telefonunuzda bir not defterinde oluşturabilirsiniz.

- K: (intensts.json dosyasında tag
- U: (intensts.json dosyasında patterns)
- A: (intensts.json dosyasında responses)'i ı temsil eder.)

Yararlanılan kaynaklar:
- https://github.com/patrickloeber/pytorch-chatbot
- OpenAI ChatGPT3.5
