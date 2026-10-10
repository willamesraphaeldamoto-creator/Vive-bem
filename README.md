# Vive Bem — Expo / Android

Aplicativo React Native com Expo, identificador Android `com.appfamilia.br`.

## Recursos
- Lembretes locais diários para dormir e acordar.
- Rotinas editáveis e salvas no aparelho.
- Mascote preguiça Vive Bem.
- Área de apoio via Pix com QR contendo a chave em texto.
- Assistente opcional OpenRouter, configurado pelo usuário.

## Rodar no Expo Go
1. Instale Node.js LTS.
2. Execute `npm install`.
3. Execute `npx expo start`.
4. Leia o QR pelo Expo Go.

## APK
Abra **Actions → Build Vive Bem APK → Run workflow**. Ao concluir, baixe o artefato `vive-bem-apk` da execução.

## Limitações e segurança
O app agenda notificações locais; não configura diretamente o despertador nativo. O QR Pix contém apenas a chave como texto e não é um QR de cobrança EMV. Não há validação automática de pagamentos ou comprovantes: isso exige API de um provedor de pagamentos e backend. Não publique chaves OpenRouter no código. O Firebase informado não foi integrado a login/contas neste projeto.
