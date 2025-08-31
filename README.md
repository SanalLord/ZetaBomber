Zeta-SmsBomber
It's centdecente to make a man go crazy

Hits

Dods

Kurulum
git clone https://github.com/CentDecente/smsbomber.git
cd smsbomber
pip3 install -r requirements.txt
python3 smsbomber.py
Discord Bot
Bot'un çalışabilmesi için 'Privileged Gateway Intents' seçeneklerinin hepsinin aktif olması gerekmektedir.

Discord Selfbot
Token bulma:

1- Tarayıcıdan bot olarak kullanacağınız Discord hesabına giriniz.
2- Tarayıcı konsolunu açınız.
3- Ağ trafiği izleme bölümüne geliniz.
4- Konsolu kapatmadan, Discord'da bu oturum boyunca tıklamadığınız bir sohbete tıklayınız.
5- Sonu messages?limit=50 ile biten isteğe tıklayınız.
6- İsteğin Header kısmındaki Authorization değeri sizin token'ınızdır.
7- Bu token'ı discord-selfbot-centdecente.py'de token kısmına yazınız. (str olarak)

Chat Id Bulma:

1- Bot hesabı ile mesajlaşacağınız kendi orijinal hesabınızdan bot'a bir tane mesaj atınız.
2- Tarayıcıda Discord'u açın ve bot hesabına giriş yapınız, ardından gerçek hesabınızın üzerine tıklayın.
3- Url'deki @me'den sonraki sayı sizin sohbet id'nizdir.
4- Bu id'yi discord-selfbot-centdecente.py'de chat_id kısmına yazınız. (int olarak)

Not: Eğer bot'u Discord sunucusunda kullanacaksanız, channels'dan sonra gelen, taksim ile ayrılmış iki sayıdan ikincisi sohbet id'nizdir.
