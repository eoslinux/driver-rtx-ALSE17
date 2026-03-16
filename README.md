# NVIDIA Driver Installer for Astra Linux 1.7

Скрипт для автоматической установки драйверов NVIDIA на Astra Linux 1.7.

## Возможности

- 🚀 Автоматическая настройка официальных репозиториев Astra Linux
- 📋 Меню выбора версии драйвера (510–580) с поддержкой стрелок
- 🛠️ Установка `nvidia-driver-*` и `nvidia-detect-*`
- 🗑️ Самоудаление папки со скриптом после установки
- 🔄 Автоматическая перезагрузка системы

## Установка

```bash
git clone https://github.com/eoslinux/driver-rtx-ALSE17.git
cd -RTX-ALSE17-510---580
sudo ./install-nvidia.sh
