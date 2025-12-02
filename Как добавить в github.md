## **1. Создай пустой репозиторий на GitHub**

1. Зайди на GitHub → нажми **New repository**
    
2. Укажи название (например, `md-project`)
    
3. Ничего не добавляй (не README, не .gitignore)
    
4. Нажми **Create repository**
    
5. GitHub покажет страницу с инструкциями — она пригодится.
    

---

## **2. Открой CMD в папке с файлами**

Перейди в папку через командную строку, например:

`cd C:\Users\You\Documents\my_md_files`
Если папка с пробелом,то используй " "

---

## **3. Инициализируй репозиторий**

`git init`

---

## **4. Добавь все файлы**

`git add .`

---

## **5. Сделай первый коммит**

`git commit -m "Initial commit"`

---

## **6. Подключи удалённый репозиторий на GitHub**

Здесь используй ссылку, которую GitHub дал тебе после создания репозитория.

Например, если у тебя HTTPS:

`git remote add origin https://github.com/USERNAME/md-project.git`

---

## **7. Отправь файлы на GitHub**

`git push -u origin master`


## **8. Скачать себе на другое устройство**

`git clone https://github.com/USERNAME/REPO.git`

Чтобы обновления проекта скачать:

`git pull`