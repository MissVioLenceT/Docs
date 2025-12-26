---
title: Konsol Komutları
order: 2
---

# {{ $frontmatter.title }}

Bu işlem komut/panel/sağlayıcı üzerinden komut çalıştırılmasını sağlar. Bir oyuncuya elmas ver gibi işlevi vardır.

## Format

* `console: <command>`

## Örnek

* `console: say Hello {player}!`
* `console: Oyuncuya Merhaba de {player}!`

* Üstteki ( {} ) bölümü placeholders çağrısıdır. Direkt konsol üzerinden işlem görür ve sadece o oyuncuya gözükür.
* player bölümü geçerli oyuncu içindir. Özel bir oyuncuya verilecek ise o kişinin ismi yazılmalıdır. Örnek: abc123 ile player aynı kişiler değildir. Birisi özel isim diğeri ise "genel" oyuncu adıdır.
