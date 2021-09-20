# GameXbot 
[![Build Status](https://travis-ci.org/jacklul/inlinegamesbot.svg?branch=master)](https://travis-ci.org/jacklul/inlinegamesbot) [![License](https://img.shields.io/github/license/jacklul/inlinegamesbot.svg)](https://github.com/jacklul/inlinegamesbot/blob/master/LICENSE) [![Telegram](https://img.shields.io/badge/Telegram-%40boot_gamebot-blue.svg)](https://telegram.me/boot_gamebot)

Bot Telegram yang menyediakan game multipemain waktu nyata yang dapat dimainkan di obrolan apa pun.

Anda dapat melihat bot beraksi dengan mengirim pesan ke [@boot_gamebot](https://telegram.me/boot_gamebot).

#### Currently available games:

- Tic-Tac-Toe
- Tic-Tac-Four ([@DO97](https://github.com/DO97))
- Elephant XO ([@DO97](https://github.com/DO97))
- Connect Four
- Rock-Paper-Scissors
- Rock-Paper-Scissors-Lizard-Spock ([@DO97](https://github.com/DO97))
- Russian Roulette
- Checkers
- Pool Checkers

## Deploying

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/fjgaming212/GameXbot)

Dengan asumsi semuanya dimasukkan dengan benar, proses penyebaran harus menjalankan perintah berikut secara otomatis dan bot Anda akan langsung berfungsi:
- `php bin/console install` - install database schema
- `php bin/console set` - set the webhook

Jika tidak, Anda harus membuka konsol aplikasi dan menjalankannya secara manual.

Jika Anda telah memverifikasi akun Heroku, Anda juga ingin menambahkan addon Heroku Scheduler dan mengatur tugas per jam untuk menjalankan perintah berikut untuk membersihkan game yang kedaluwarsa dari database:
- `php bin/console cron`

## Catatan terjemahan

Dukungan terjemahan diterapkan tetapi tidak digunakan terutama karena teks yang diterjemahkan akan ditampilkan kepada kedua pemain - ini bisa menjadi masalah dalam grup "permainan" - orang-orang yang mengatur bahasa yang tidak dapat dipahami oleh pemain lain!

## Contributing

See [CONTRIBUTING](CONTRIBUTING.md) for more information.

## License

See [LICENSE](LICENSE).

Thanks 

[Jackul](https://github.com/jacklul)

[Apis](https://github.com/apisuserbot)

## Contact Developer

[![Telegram](https://img.shields.io/badge/Telegram-%40Rizzz-blue.svg)](https://telegram.me/FJ_GAMING)
