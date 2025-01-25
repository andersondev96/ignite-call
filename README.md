# Ignite Call

![GitHub language count](https://img.shields.io/github/languages/count/andersondev96/ignite-call?style=for-the-badge&color=00b37e)
![GitHub repo size](https://img.shields.io/github/repo-size/andersondev96/ignite-call?style=for-the-badge&color=00b37e)
![GitHub last commit](https://img.shields.io/github/last-commit/andersondev96/ignite-call?style=for-the-badge&color=00b37e)

![Home](./home.png)

Aplicação voltada para barbearias permitindo que as pessoas façam o seu agendamento.

[Sobre a a aplicação](#-sobre-a-aplicação) | [Tecnologias utilizadas](#-tecnologias-utilizadas) | [Layout](#-layout-da-aplicação) | [Como executar a aplicação](#-como-executar-a-aplicação) | [Deploy da aplicação](#-tecnologias-utilizadas) | [Como contribuir](#-como-contribuir) | [Licença](#-licença) | [Autor](#-autor)

## 📄 Sobre a aplicação
A aplicação é voltada para barbearias e permite que as pessoas escolham uma data e um horário no calendário e façam o seu agendamento.

### Features da aplicação
- [x] Cadastro de usuário
- [x] Conexão com calendário
- [x] Configuração de disponibilidade
- [x] Atualização do perfil
- [x] Calendário de disponibilidade
- [x] Agendamento

## 🧑‍💻 Tecnologias utilizadas
[![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](https://react.dev/)
[![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
[![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)](https://www.prisma.io/)
[![React Query](https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white)](https://tanstack.com/query/latest/docs/framework/react/overview)
[![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)](https://console.cloud.google.com/)
[![Zod](https://img.shields.io/badge/zod-%233068b7.svg?style=for-the-badge&logo=zod&logoColor=white)](https://zod.dev/)
[![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)

## 🎨 Layout da aplicação
Para acessar o layout da aplicação, você precisará ter uma conta criada no [Figma](https://www.figma.com). 

Caso já tenha uma conta acesse clicando no link abaixo:

- [Layout do Figma](https://www.figma.com/design/7Gt1aTyffcSD4V2PmF2BLK/Ignite-Call-(Community)?node-id=339-74&t=uEOHfIP0DRRtzLxR-1)

## 🚀 Como executar a aplicação

> ### Pré-requisitos:
> 
> É necessário ter instalado em sua máquina o Git e Node (versão LTS).

- Clone esse repositório
```
git clone https://github.com/andersondev96/ignite-call
```
- Acesse a pasta do projeto:
```
cd ignite-call
```
- Instale as dependências
```
npm install
```
- Renomeie o arquivo `.env.example` para `.env` e utilize as suas próprias chaves.
```
cp .env.example .env
```
- Rode o comando para criar as `migrations` do prisma:
```
npx prisma migrate dev
```
- Execute a aplicação:
```
npm run dev
```
- A aplicação será executada na porta `3000`, utilize o *brower* de sua preferência.

## ⚙️ Deploy da aplicação
A aplicação está disponível online nesse [endereço](https://ignite-call-anderson.vercel.app/)

O deploy da aplicação foi feito utilizando o [Vecel](https://vercel.com/)

## 🤝 Como contribuir?
- Faça um *fork* desse repositório.
- Crie uma *branch* com a sua feature: `git checkout -b my-feature`.
- Faça um commit das suas alterações: `git commit -m 'feat: My new feature'`.
- Faça um push para a sua branch: `git clone origin my-feature`.

Depois que o *merge* da sua *pull request* for feito, você poderá deletar a sua *branch*.

## 📝 Licença
Esse projeto está sobre a licensa [MIT](LICENSE)

## 👥 Autor

<img src="https://avatars.githubusercontent.com/u/49786548?v=4" width="64" style="border: 2px solid; border-radius: 50px" />

**Anderson Fernandes Ferreira**

[![instagram](https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/anderson_ff13)
[![email](https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white)](mailto:andersonfferreira96@gmail.com.br)
[![linkedin](https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anderson-fernandes96/)

Feito com 💚 por Anderson Fernandes 👋 [Entre em contato!](https://www.linkedin.com/in/anderson-fernandes96/)





