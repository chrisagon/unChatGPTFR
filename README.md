<div align="center"><img src="https://github.com/chrisagon/unChatGPTFR/blob/main/chatgpt3000.png?raw=true" width="50%"></div>

# unChatGPTFR 3000

unChatGPTFR 3000 est la version FR de unChatGPT. C'est une interface web qui utilise l'API OpenAI pour créer une expérience de chatbot. Il permet aux utilisateurs de converser avec un chatbot basé sur l'IA, de manière similaire à ChatGPT, mais sans avoir à attendre dans une file d'attente ou à avoir un accès limité. unChatGPT est conçu pour fournir un moyen facile et efficace de discuter avec un chatbot basé sur l'IA de manière rapide et intuitive.

### Pourquoi unChatGPTFR 3000 ?
3000, c'est pour mémoriser le port de l'url sur votre serveur. Quand vous aurez installez et lancez l'application vous aurez une adresse de type http://openvm:3000/ ou http://nomduserveur:3000/

<div align="center"><a href="https://www.producthunt.com/posts/unchatgpt?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-unchatgpt" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=377698&theme=light" alt="unChatGPT - ChatGPT&#0032;is&#0032;at&#0032;capacity&#0063;&#0032;Use&#0032;the&#0032;OpenAI&#0032;API&#0032;with&#0032;unChatGPT | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a></div>

## Démarrage

### Installer les dependences

Pour commencer avec unChatGPT, clonez le dépôt et installez les dépendances :

```
git clone
cd unChatGPTFR
npm install
```

### Créer une clé API OpenAI

unChatGPT utilise l'API OpenAI pour générer des réponses. Pour utiliser l'API OpenAI, vous devez créer une clé API. Pour créer une clé API, suivez les instructions sur le [site web OpenAI] (https://platform.openai.com/account/api-keys).

### Environment Variables

Copy the `.env.sample` file to `.env`

```
cp .env.sample .env

```

and add your OpenAI API key to the file:

```
OPENAI_API_KEY      (required)
OPENAI_MODEL        (optional, default: "text-davinci-003")
OPENAI_MAX_TOKENS   (optional, default: "3840")
```

## Usage

Pour démarrer le chatbot, exécutez la commande suivante :

```
npm run build
npm run start
```

ou si vous souhaitez utiliser la version de développement :

```
npm run dev
```

Le chatbot démarre et vous pouvez commencer à interagir avec lui. Pour arrêter le chatbot, appuyez sur Ctrl+C.

## Disclaimer

unChatGPT is not affiliated with OpenAI. unChatGPT is a clone of ChatGPT, which is an open source project developed by OpenAI. unChatGPT is not endorsed by OpenAI.
