# Getting Started
Install the dependencies and run the project
```
npm install
npm start
```

Head over to https://vitejs.dev/ to learn more about configuring vite

High level diagram of this application:

### This Application generates a report on stock prices based on selected stock ticker.
## Frontend application gets the stock data from polygon api.
## Passes the stock data and prompt information over to worker
## Worker connects to openai gpt4.1-mini model through Cloudflare AI Proxy, to get the predictions based on the provided prompt.
## Cloudflare AI proxy is used for obervability purposes and it also allows other features like caching, to avoid invoking model.
## Frontend is deployed as pages and backend as worker in cloudflare.

<img width="871" alt="Screenshot 2025-06-04 at 2 43 53 PM" src="https://github.com/user-attachments/assets/ef53dc16-7f3a-4ab9-950a-e193e8431e27" />



## About Scrimba

At Scrimba our goal is to create the best possible coding school at the cost of a gym membership! 💜
If we succeed with this, it will give anyone who wants to become a software developer a realistic shot at succeeding, regardless of where they live and the size of their wallets 🎉
The Frontend Developer Career Path aims to teach you everything you need to become a Junior Developer, or you could take a deep-dive with one of our advanced courses 🚀

- [Our courses](https://scrimba.com/allcourses)
- [The Frontend Career Path](https://scrimba.com/learn/frontend)
- [Become a Scrimba Pro member](https://scrimba.com/pricing)

Happy Coding!
