# Pizza Play — Árvore de links

Página estática e responsiva com os principais canais da Pizza Play, em Ipatinga/MG.

## Executar localmente

Não precisa instalar dependências nem compilar:

```sh
python3 -m http.server 8000
```

Abra http://localhost:8000. Também é possível abrir `index.html` diretamente.

## Estrutura

- `index.html`: página, estilos responsivos e links.
- `assets/logo.png`: logotipo original da Pizza Play.

## Conteúdo

Cardápio Hubt, pedidos de reserva e aniversário via WhatsApp, Instagram e localização no Google Maps. Reservas dependem de confirmação pela equipe.

O WhatsApp usado é o principal exibido no cardápio Hubt: (31) 99820-6781. Há outro número em diretórios públicos; confirme o canal operacional antes de divulgar. O Instagram `@pizzaplayipatinga` foi identificado no dossiê da marca e não teve disponibilidade verificada ao vivo.

## Hospedagem

Compatível com qualquer hospedagem estática, servindo esta pasta como raiz. Nenhum backend, segredo, rastreador ou integração de pagamentos é incluído. A inclusão dos arquivos no repositório não configura automaticamente uma hospedagem.
