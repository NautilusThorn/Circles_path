# Circles_path
my way along Bash
Этим файлом начинается мой путь в мир цифры. Меня зовут Nautilus. Мне 53, но я рискнул
Это мой первый цикл, который я собрас обучаясь у нейросети DeepSeek.
Это обратный отчет от 9 до 0 с вставкой для юмора одного известного персонажа.
```Bash
#!/bin/bash
n=9
echo "Убить всех человеков!   Бендер Б. Родригез"
while [ $n -gt 0 ]
do
echo "Помните меня! $n"
sleep 1
n=$((n - 1))
done
echo "Внимание владельцу зеленого Кадилака! А хотя..."
sleep 5
echo "Ka- booooooom"


# 27.04.2026
сегодня сделал простую игру
# это игра "Угадай число 36"
```Bash
#!/bin/bash
while true
do
echo  "Угадай число от 0 до 50 "
read answer
if [ "$answer" -gt 36 ]
then
echo "Ваше число $answer, но это больше чем я загадал"
elif [ "$answer" -lt 36 ]
then
echo "Ваше число $answer, но это меньше чем я загадал"
else
echo "Угадал"
break
fi
done
