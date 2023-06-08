# WEBGL_LABS_2
Calculation&graphics work (Spatial audio)

Sydorenko Roman 22 Variant

Requirements
  - reuse the code from practical assignment #2;
  - implement sound source rotation around the geometrical center of the surface patch by means of tangible interface (the surface stays still this time and the sound source moves). Reproduce your favorite song in mp3/ogg format having the spatial position of the sound source controlled by the user;
  - visualize position of the sound source with a sphere;
  - add a sound filter (use BiquadFilterNode interface) per variant. Add checkbox element that enables or disables the filter. Set filter parameters according to your taste.

link to test in Chrome Android (test audio in headphones): https://cgw.romadjan25.repl.co

Process Flow:
1. Перевірити чи є магнетометр на девайсі
2. Так як по-дефолту магнетометр програмно не підтримується в Chrome Android, скористаємося підказкою, і поставимо прапорець Enabled for Generic Sensor Extra Classes
3. Ввімкнути відтворення аудіо
4. Обертати смартфон щоб змінювати джерело звуку
5. Спробувати фільтр низьких частот

![image](https://github.com/romadjan/WEBGL_LABS_2/assets/81487530/e8e11b3a-5c1c-4a94-8082-76fcaa9cf444)

![image](https://github.com/romadjan/WEBGL_LABS_2/assets/81487530/fc92247c-ec9a-4d2c-b6db-c2dc168e3657)

3. Відео роботи (щоб зрозуміти, що програма працює, було знято відтворення аудіо без навушників, при тестування за лінкою наданою вище краще використовувати наушники):
 https://www.youtube.com/shorts/r5HCEA9eOMU

4. Висновок: Об'єкт магенетометра повертає магнітне поле по 3 координатам телефона. Спроєціювавши вектор на площину XoZ і визначивши його відхилення програма дозволяє точно переміщати джерело звуку і відповідно сферу в інтерфейсі повертаючи смартфон по одній вісі системи координат WebGL. В ході розробки програми було виявлено, що при проекціюванні вектору на площини XoY та YoZ бажаного результату програма не дає.
Робота із аудіо була забезпечена за допомогою Web Audio API- що дозволяє відтворювати, створювати та керувати звуком, додавати звукові ефекти, створювати візуалізацію аудіо та багато іншого за допомогою JavaScript у браузері.
