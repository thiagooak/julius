# Julius

> "Se eu não comprar nada o desconto é bem maior" - [Julius](https://youtu.be/qjkaCajt4RY?t=100)

## Get your data

* Go to the [Nubank web app](https://app.nubank.com.br/)
* Open developer tools and go to `network`
* Find the requests with JSON responses of your bills (one request per month)
* Save them to the `data` folder

## Run

* `pip install -r requirements.txt`
* `./julius ./data/filename.json`

## Screenshot

![example](https://user-images.githubusercontent.com/124720/233878983-8c9982f2-7ba0-42ed-8048-7610649f43f5.png)
