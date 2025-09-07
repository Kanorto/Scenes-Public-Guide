## Disclaimer:
---
Русская версия

Все материалы, размещённые в данном репозитории, являются оригинальными произведениями, созданными автором на основе вдохновения оригинальным гайдом. Перевод и адаптация оригинального гайда на русский язык осуществлены исключительно с целью повышения удобства и информированности пользователей и читателей. Автор не имеет намерения нанести ущерб каким-либо лицам, не нарушает авторские права и предоставляет материалы исключительно для бесплатного и законного использования.


---

English Version

All materials published in this repository are original works created by the author, inspired by the original guide. The translation and adaptation of the original guide into Russian have been carried out solely to enhance the convenience and information available to users and readers. The author does not intend to cause harm to any party, does not infringe on any copyrights, and provides the materials exclusively for free and lawful use.

---

Данное руководство поможет вам установить и настроить сцены на сервере Minecraft с использованием ModelEngine, MythicMobs и DeluxeMenus. Выполняйте шаги внимательно, чтобы избежать ошибок.

### Посмотреть Видео от автора можно в [отдельном файле](https://github.com/Kanorto/Scenes-Public-Guide/blob/main/VideoGuide). 

---

## Оглавление

1. [Все ссылки](#ссылки)  
2. [Установка плагинов на сервер](#установка-плагинов-на-сервер)  
3. [Добавление скинов](#добавление-скинов)  
4. [DeluxeMenus](#deluxemenus)  
5. [Перезагрузка плагинов и ресурс-пака](#перезагрузка-плагинов-и-ресурс-пака)  
6. [Добавление звуков (опционально)](#добавление-звуков-опционально)  
7. [Как использовать сцены](#как-использовать-сцены)

---

## Ссылки

### Scenes (на [Black-minecraft.com](https://black-minecraft.com) и скачанное с нуллфорумс(будьте внимательны!)) 
  
**Environment**
- [Голуби](https://black-minecraft.com/resources/scenes-pigeons-environment.7999/) 
- [Бабочки](https://black-minecraft.com/resources/scenes-butterflies-environment.7989/) 
- [Вороны](https://black-minecraft.com/resources/scenes-crows-environment.7988/) 
- [Колокольчики по ветру](https://black-minecraft.com/resources/scenes-wind-chimes-environment.7998/)
- [Пауки (СКАЧАНО С NULLFORUMS!)](https://www.dropbox.com/scl/fi/74k4v7e2cgfjtjv647ply/scenes_spiders.zip?rlkey=0kngowhr73ezddvd3isur9cog&st=c546sa45&dl=0)
- [Транспорт путников(СКАЧАНО С NULLFORUMS!)](https://www.dropbox.com/scl/fi/87dc1c8fxkikv0yxe0yu9/4.0_scenes_wanderers_transport_vol1.zip?rlkey=hq9r4yn8mfbe2ckiwcs3u4pxv&st=imv6k23k&dl=0)
- [Лозы(СКАЧАНО С NULLFORUMS!)](https://www.dropbox.com/scl/fi/3xzg0fhmzyu894b9axpbe/Scenes-jungle-vines.zip?rlkey=gvuwh3juhjopnzqed25n9mxwc&st=9g93qdwl&dl=0)
  
**NPCS**
  
- [Жители города 1+2 (Были удалены с Black-Minecraft)](https://www.dropbox.com/scl/fi/6cy4jmtry569fjsds3ph3/scenes_townsfolks_vol1-2.zip?rlkey=kdm3li0dpkeqm2g4bcf3lqfo0&st=esawnm6a&dl=0)
- [Жители города 3](https://black-minecraft.com/resources/scenes-townsfolks-vol-3-npc.8876/)
- [Жители города 4 (Sponsor role need)](https://black-minecraft.com/resources/scenes-townsfolks-vol-4-npc.8886/)
- [Рыбак](https://black-minecraft.com/resources/scenes-fishermen-npc.9038/)
- [Кузнец](https://black-minecraft.com/resources/scenes-blacksmith-npc.7846/) 
- [Фермер](https://black-minecraft.com/resources/scenes-farmers-npc.9037/)
- [Боевые 1](https://black-minecraft.com/resources/scenes-combat-vol-1-npc.8881/)
- [Шахтеры 1 (СКАЧАНО С NULLFORUMS!](https://www.dropbox.com/scl/fi/tmah3d9kmsl9fca2kxhba/Scenes-Miners-1.zip?rlkey=zw7z9qrkq4jqogdyvsa2vx1ig&st=fbh9mqb0&dl=0)
- [Путники 1 (СКАЧАНО С NULLFORUMS!](https://www.dropbox.com/scl/fi/sj7ismn60i4bjoc3d1wax/Scenes-wanderers-vol-1-1.zip?rlkey=zvxvnrvpoodjtx8f41zj9feml&st=85nm1xqg&dl=0)
- [Охранники 1(СКАЧАНО С NULLFORUMS!)](https://www.dropbox.com/scl/fi/292elcmjm50os9hzayezh/Scenes-guards-vol-1-1.zip?rlkey=bexljcge1su0mwz0mkp4rpypg&st=t7tiyfkh&dl=0)
  
**Скрипт [Создание меню и bbmodel](https://black-minecraft.com/resources/scenes-tool-change-skin.8640/)**

### Plugins **original**
- [ModelEngine 4.0](https://www.spigotmc.org/resources/modelengine.79477/)  
- [MythicMobs Premium](https://www.mythicmobs.net/index.php?pages/store/)  
- [DeluxeMenus](https://www.spigotmc.org/resources/deluxemenus.11734/)

### Plugins (on [Black-minecraft.com](https://black-minecraft.com)) 
- [Black MythicMobs Dev](https://black-minecraft.com/resources/mythicmobs-dev-builds-premium.4171/ )
- [Black MythicMobs](https://black-minecraft.com/resources/mythicmobs-premium.1180/) 
- [Black Itemsadder](https://black-minecraft.com/resources/itemsadder.27/)
- [Black Model Engine Dev premium](https://black-minecraft.com/resources/model-engine-premium-4-x.3815/)
- [Black Model Engine premium](https://black-minecraft.com/resources/conxeptworks-model-engine.1086/)  

---

## Установка плагинов на сервер

### **Важно:**
Если вы приобрели несколько NPC-паков, размещайте их по очереди от самого старого к новому, чтобы избежать конфликтов и перезаписи конфигураций.

### **Drag and Drop:**
Просто перенесите папку `plugins` из архива в директорию сервера. Это **не перезапишет** существующие файлы, а добавит новые сцены.

---

## Добавление скинов

> Примечание: Скины, которые вы загружаете и используете, должны быть в формате 64x64, а не в устаревшем формате 64x32.
> Имя скина не должно содержать заглавных букв или специальных символов, иначе ModelEngine не сможет его загрузить.

Используйте [скрипт](https://black-minecraft.com/resources/scenes-tool-change-skin.8640/) для создания bbmodel и меню. Для этого загрузите архив, переместите ваши скины (желательно весь сразу чтобы потом не ломать меню), и запустите скрипт.
После его завершения конфигурации DeluxeMenus надо поместить из `папка выполнения скрипта/menus` в: `plugins\DeluxeMenus\gui_menus`. Все файлы из папки `output` надо перенести в `plugins/ModelEngine/blueprints/Scenes/Scenes/Skins` 

***Все меню надо прописать в основной конфигурации `plugins/DeluxeMenus/config.yml`***

---

## Перезагрузка плагинов и ресурс-пака

### Используйте команды:

- **MythicMobs:**  
    `/mm reload`
    
- **ModelEngine:**  
    `/meg reload`
    
- **DeluxeMenus:**  
    `/dm reload`
    

### Обновление ресурс-пака:

> Можно использовать Nexo, ItemsAdder для генерации и обновления ресурс пака. Проверьте что в ItemsAdder у вас подхватывается ресурспак из ModelEngine:
```
merge_other_plugins_resourcepacks_folders:
    - ModelEngine/resource pack
```

---

## Как использовать сцены

### Установка NPC, применение скинов и косметики:

1. Введите команду:  
    `/scenes`
    
2. Найдите нужного NPC и заспавните его.
    
3. **Нажмите Ctrl + ПКМ** по NPC для открытия редактора.
    
4. После выбора скинов и косметики выполните:  
    `/save-all`
    
5. Затем:  
    `/mm reload`
    

> Это сохранит изменения и предотвратит сброс после перезагрузки.

> Убедитесь, что у вас есть права **OP** и `scenes.use`.

---

### Движущиеся NPC и Pins

1. Встаньте на точку, где хотите разместить Pin.
2. Используйте:

```bash
/mm pins create [ pack (выберите один из предложенных паков в чате) ] [ Pin's name ]
```
> **Важно:** Не используйте `Mythic` как pack — это не будет работать.  
> Если не видите доступный pack, создайте новый и поместите его в папку `mythicmobs/packs`(создайте новую папку лол).

3. Имя Pin'а можно найти в описании NPC в сцене.  
    Примеры: `mine1`, `mine2`, `farm3`, `farm4`, `lumberjack5`, `lumberjack6`


---

## Добавление звуков (Неактуально!)

Если вы хотите добавить звуки к сценам, у вас есть два варианта:


### Option 1: Через плагин-менеджер ресурспаков

Например: **Nexo**, **ItemsAdder**

### Option 2: Вручную

1. Добавьте `.ogg` файлы в папку `sounds` вашего ресурспака.
2. Используйте Discord-бота для генерации `sounds.json`.  
    Отправьте ему название папки и именя звуков.
3. Вставьте сгенерированные строки в `sounds.json`.

### Настройка в MythicMobs:

- Откройте папку MythicMobs.
- Перейдите в `Mobs`, выберите нужный конфиг.
- Найдите блок, похожий на:

```yaml
interact_1:
  Cooldown: 8.7083
  Skills:
  # - sound{s=your_sound_name} @self
  - state{s=interact;mid=scene_townsfold_1;lo=4;li=4} @self
  - lockhead{lp=true} @self
```

Замените `your_sound_name` на ваш звук, и **уберите `#`** в строке `sound`.



 
