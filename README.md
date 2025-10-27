Gerar APK

1ª forma:
Deve-se ter uma conta em https://expo.dev/
Na pasta do projeto faça o login 
npx expo login

instale o EAS – expo application service
npm install -g eas-cli

logar no site expo.dev e configura o eas.json  
eas build:configure

em eas.json
gerar o apk – de forma online
eas build -p android --profile preview

cuidado aqui!!!
Seu projeto entra na fila de apk – e fica build queued
Isso pode levar vários minutos

Depois de gerado o apk abra o link 
Baixe o apk ou usar o qrcode para baixar direto no celular
Upar ele no google drive
criar um qrcode
e instalar o celular

se der erro== verifica o erro
npx tsc –noEmit
ou
npx expo-doctor

