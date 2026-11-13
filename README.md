# Baby Growth

Acompanhamento da gestação em português, pensado primeiro para o celular.

## Recursos

- Idade gestacional calculada pela data provável do parto ou configurada manualmente em semanas e dias.
- Comparação semanal de tamanho e peso com referências educativas aproximadas.
- Gráfico SVG de evolução e painel preparado para receber um modelo 3D.
- Preferências guardadas localmente neste dispositivo.

## Publicação

O workflow em `.github/workflows/pages.yml` publica o site pelo GitHub Pages a cada atualização da branch `main`. Em **Settings → Pages**, escolha **GitHub Actions** como origem se necessário.

## Privacidade e precisão

As preferências ficam no `localStorage` deste navegador; não há conta nem sincronização entre dispositivos. Para compartilhar os mesmos dados com outra pessoa, será necessário adicionar um serviço de sincronização. Comparações e gráficos são referências educativas aproximadas, não medições individuais nem orientação médica.
