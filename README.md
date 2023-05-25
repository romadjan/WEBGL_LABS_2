# WEBGL_LABS_2
PA2 Tangible interface

Sydorenko Roman 22 Variant

Implement surface rotation based on hardware magnetometer sensor readings

link to test in Chrome Android: https://tangible-interface.romadjan25.repl.co

Process Flow:
1. Перевірити чи є магнетометр на девайсі
2. Так як по-дефолту магнетометр програмно не підтримується в Chrome Android, скористаємося підказкою, і поставимо прапорець Enabled for Generic Sensor Extra Classes

![image](https://github.com/romadjan/WEBGL_LABS_2/assets/81487530/e8e11b3a-5c1c-4a94-8082-76fcaa9cf444)

![image](https://github.com/romadjan/WEBGL_LABS_2/assets/81487530/fc92247c-ec9a-4d2c-b6db-c2dc168e3657)

3. Відео роботи:
https://www.youtube.com/shorts/Nf-DHix3E1s


4. Висновок: Об'єкт магенетометра повертає магнітне поле по 3 координатам телефона. Спроєціювавши вектор на площину XoZ і визначивши його відхилення програма дозволяє точно обертати фігуру по одній вісі системи координат WebGL. В ході розробки програми було виявлено, що при проеціюванні вектору на площини XoY та YoZ бажаного результату програма не дає
