<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00c6ff,100:0072ff&height=220&section=header&text=Muslimbek%20Muxtorov&fontSize=50&fontColor=ffffff&animation=fadeIn&fontAlignY=35"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=2500&pause=800&color=00C6FF&center=true&vCenter=true&width=700&lines=Python+Developer+%F0%9F%90%8D;C%2B%2B+Programmer+%F0%9F%92%BB;Robotics+Developer+%F0%9F%A4%96;Arduino+Developer+%F0%9F%94%8C;LEGO+SPIKE+%F0%9F%A4%96;Web+Developer+%F0%9F%8C%90;UI%2FUX+Designer+%F0%9F%8E%A8"/>

<br>

<img src="https://komarev.com/ghpvc/?username=muxtorovmuslimbek167-glitch&label=Profile%20Views&color=0e75b6&style=for-the-badge"/>

</div>

---

# 👋 Salom! Men Muslimbek Muxtorov

<div align="center">

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="450">

</div>

Men dasturlash, robototexnika, web texnologiyalar va dizaynga qiziqaman.

Men Python, C++, HTML, CSS, JavaScript, Scratch, Arduino, LEGO SPIKE, LEGO WeDo, Makerzoid, Figma va Canva bilan ishlayman.

---

# 🚀 Men haqimda

```text
👨‍💻 Programmer
🤖 Robotics Developer
🌐 Web Developer
🎨 Designer
🔌 Arduino Developer
🐍 Python Developer
💻 C++ Programmer
```

---

# 🧠 Mening texnologiyalarim

<div align="center">

### 💻 Programming

<img src="https://skillicons.dev/icons?i=python,cpp,html,css,js"/>

### 🤖 Robotics

<img src="https://skillicons.dev/icons?i=arduino"/>

### 🎨 Design

<img src="https://skillicons.dev/icons?i=figma"/>

</div>

---

# 🛠️ Men biladigan texnologiyalar

| Texnologiya | Holat |
|---|---|
| 🐍 Python | 🟢 Bilaman |
| 💻 C++ | 🟢 Bilaman |
| 🌐 HTML | 🟢 Bilaman |
| 🎨 CSS | 🟢 Bilaman |
| ⚡ JavaScript | 🟡 O‘rganmoqdaman |
| 🧩 Scratch | 🟢 Bilaman |
| 🤖 LEGO SPIKE | 🟢 Bilaman |
| 🧱 LEGO WeDo | 🟢 Bilaman |
| ⚙️ Makerzoid | 🟢 Bilaman |
| 🎨 Figma | 🟢 Bilaman |
| 🖌️ Canva | 🟢 Bilaman |
| 🔌 Arduino | 🟢 Bilaman |

---

# 📊 Skill Level

```text
🐍 Python        ████████████████░░░░ 80%
💻 C++           ██████████████░░░░░░ 70%
🌐 HTML          ██████████████████░░ 90%
🎨 CSS           ████████████████░░░░ 80%
⚡ JavaScript    ██████████░░░░░░░░░░ 50%
🔌 Arduino       ████████████████░░░░ 80%
🤖 SPIKE         ██████████████████░░ 90%
🧱 WeDo          ██████████████████░░ 90%
⚙️ Makerzoid     ████████████████░░░░ 80%
🎨 Figma         ████████████████░░░░ 80%
🖌️ Canva         ██████████████████░░ 90%
🧩 Scratch       ██████████████████░░ 90%
```

---

# 🐍 Python

<div align="center">

<img src="https://media.giphy.com/media/KAq5w47R9rmTuvWOWa/giphy.gif" width="350">

</div>

Python yordamida dasturlar, kalkulyatorlar, o‘yinlar va turli loyihalar yarataman.

### 🔢 Python Calculator

```python
def calculator():

    print("╔════════════════════════╗")
    print("║    PYTHON CALCULATOR   ║")
    print("╚════════════════════════╝")

    a = float(input("Birinchi son: "))
    operation = input("Amal (+ - * /): ")
    b = float(input("Ikkinchi son: "))

    if operation == "+":
        result = a + b

    elif operation == "-":
        result = a - b

    elif operation == "*":
        result = a * b

    elif operation == "/":

        if b == 0:
            print("❌ 0 ga bo‘lish mumkin emas!")
            return

        result = a / b

    else:
        print("❌ Noto‘g‘ri amal!")
        return

    print("✅ Natija:", result)


calculator()
```

---

# 🎮 Python Mini Game

```python
import random

secret = random.randint(1, 100)

attempts = 0

print("🎮 SON TOPISH O‘YINI")
print("1 dan 100 gacha son o‘yladim!")

while True:

    try:
        guess = int(input("Sonni toping: "))

        attempts += 1

        if guess < secret:
            print("📈 Kattaroq son!")

        elif guess > secret:
            print("📉 Kichikroq son!")

        else:
            print("🎉 TOPDINGIZ!")
            print("Urinishlar:", attempts)
            break

    except ValueError:
        print("❌ Faqat son kiriting!")
```

---

# 💻 C++

<div align="center">

<img src="https://media.giphy.com/media/3oKIPnAiaMCws8nOsE/giphy.gif" width="350">

</div>

C++ yordamida algoritmlar, konsol dasturlari va elektronika loyihalari bilan ishlayman.

### 🔢 C++ Calculator

```cpp
#include <iostream>

using namespace std;

int main() {

    double a, b;
    char operation;

    cout << "========================\n";
    cout << "      C++ CALCULATOR\n";
    cout << "========================\n";

    cout << "Birinchi son: ";
    cin >> a;

    cout << "Amal (+ - * /): ";
    cin >> operation;

    cout << "Ikkinchi son: ";
    cin >> b;

    switch (operation) {

        case '+':
            cout << "Natija: " << a + b;
            break;

        case '-':
            cout << "Natija: " << a - b;
            break;

        case '*':
            cout << "Natija: " << a * b;
            break;

        case '/':

            if (b == 0)
                cout << "❌ 0 ga bo‘lish mumkin emas!";
            else
                cout << "Natija: " << a / b;

            break;

        default:
            cout << "❌ Noto‘g‘ri amal!";
    }

    return 0;
}
```

---

# 🤖 Robotics

<div align="center">

<img src="https://media.giphy.com/media/6OrCT1jVbonHG/giphy.gif" width="400">

</div>

Robototexnika mening asosiy qiziqishlarimdan biridir.

### 🤖 Platformalar

```text
🔌 Arduino
🤖 LEGO SPIKE
🧱 LEGO WeDo
⚙️ Makerzoid
🧩 Scratch
```

---

# 🔌 Arduino

<div align="center">

<img src="https://media.giphy.com/media/f3iwJFOVOwuy7K6FFw/giphy.gif" width="400">

</div>

Arduino yordamida sensorlar, LED, motor, buzzer va boshqa elektron qurilmalar bilan ishlash mumkin.

---

# 🧪 MQ-5 Gas Sensor

MQ-5 gaz sensoridan analog qiymat olinadi.

```cpp
int gasSensor = A0;

int led = 8;

int buzzer = 9;


void setup() {

    Serial.begin(9600);

    pinMode(gasSensor, INPUT);

    pinMode(led, OUTPUT);

    pinMode(buzzer, OUTPUT);
}


void loop() {

    int gas = analogRead(gasSensor);

    Serial.print("Gaz qiymati: ");
    Serial.println(gas);


    if (gas <= 400) {

        digitalWrite(led, LOW);
        digitalWrite(buzzer, LOW);

        Serial.println("✅ Gaz ko‘p emas");
    }


    else if (gas <= 800) {

        digitalWrite(led, HIGH);
        digitalWrite(buzzer, LOW);

        Serial.println("⚠️ Biroz gaz bor");
    }


    else {

        digitalWrite(led, HIGH);
        digitalWrite(buzzer, HIGH);

        Serial.println("🚨 Gaz juda ham ko‘p!");
    }


    delay(1000);
}
```

---

# 🤖 SPIKE Sumo

<div align="center">

<img src="https://media.giphy.com/media/13HgwGsXF0aiGY/giphy.gif" width="400">

</div>

SPIKE Sumo robotida sensorlar orqali raqibni aniqlash va motorlarni boshqarish mumkin.

### Robot algoritmi

```text
              🤖 START
                  │
                  ▼
           🔍 SENSOR TEKSHIR
                  │
          ┌───────┴───────┐
          │               │
       Raqib bor       Raqib yo‘q
          │               │
          ▼               ▼
      ⚡ HUJUM          🔄 QIDIR
          │               │
          └───────┬───────┘
                  │
                  ▼
                REPEAT
```

---

# 🧱 LEGO WeDo

<div align="center">

<img src="https://media.giphy.com/media/3o7TKtnuHOHHUjR38Y/giphy.gif" width="400">

</div>

LEGO WeDo yordamida motor, sensor va boshqa qismlardan foydalanib robotlar yaratish mumkin.

```text
⚙️ Motor
🔘 Sensor
🚗 Robot Car
🤖 Robot
💡 LED
```

---

# ⚙️ Makerzoid

<div align="center">

<img src="https://media.giphy.com/media/L8K62iTDkzGX6/giphy.gif" width="400">

</div>

Makerzoid orqali mexanik va robototexnika loyihalarini yaratish mumkin.

```text
🚗 Robot Car
🤖 Robot Arm
🏗️ Smart Machine
🚪 Automatic Door
🚦 Smart Traffic Light
```

---

# 🌐 Web Development

<div align="center">

<img src="https://media.giphy.com/media/ln7z2eWriiQAllfVcn/giphy.gif" width="350">

</div>

Web dasturlashda HTML, CSS va JavaScript texnologiyalaridan foydalanaman.

```text
HTML
  ↓
CSS
  ↓
JavaScript
  ↓
🌐 Website
```

---

# 🌐 HTML

```html
<!DOCTYPE html>

<html lang="uz">

<head>

    <meta charset="UTF-8">

    <title>
        Muslimbek Portfolio
    </title>

</head>

<body>

    <h1>
        Salom, GitHub! 👋
    </h1>

    <p>
        Men Muslimbek Muxtorov.
    </p>

</body>

</html>
```

---

# 🎨 Figma

<div align="center">

<img src="https://media.giphy.com/media/QHE5gWI0zqW2c/giphy.gif" width="350">

</div>

Figma yordamida:

```text
📱 Mobile UI
🌐 Web UI
🖼️ Banner
🎨 Interface
📐 Prototype
```

yaratish mumkin.

---

# 🖌️ Canva

Canva yordamida:

```text
📱 Poster
🎞️ Presentation
🖼️ Banner
📢 Social Media Design
📚 School Projects
```

tayyorlash mumkin.

---

# 🚀 My Projects

| Loyiha | Texnologiya |
|---|---|
| 🤖 Smart Robot | Arduino |
| 🧪 Gas Detector | Arduino + MQ-5 |
| 🏆 SPIKE Sumo | LEGO SPIKE |
| 🎮 Number Game | Python |
| 🧮 Calculator | Python / C++ |
| 🌐 Portfolio | HTML + CSS + JS |
| 🚗 Robot Car | Makerzoid |
| 🧱 WeDo Robot | LEGO WeDo |

---

# 🧠 Programming Flow

```text
💡 IDEA
   ↓
📝 PLAN
   ↓
💻 CODE
   ↓
🧪 TEST
   ↓
🐞 DEBUG
   ↓
🚀 BUILD
   ↓
🌍 SHARE
```

---

# 📊 GitHub Statistics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=muxtorovmuslimbek167-glitch&show_icons=true&theme=tokyonight&hide_border=true&border_radius=15"/>

<br><br>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=muxtorovmuslimbek167-glitch&layout=compact&theme=tokyonight&hide_border=true&border_radius=15"/>

<br><br>

<img src="https://streak-stats.demolab.com?user=muxtorovmuslimbek167-glitch&theme=tokyonight&hide_border=true&border_radius=15"/>

</div>

---

# 🐍 Contribution Snake

<div align="center">

<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg" width="850">

</div>

---

# 🔥 Coding Animation

<div align="center">

<img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif" width="500">

</div>

---

# 📚 Currently Learning

```text
🟢 Python
🟢 C++
🟢 Arduino
🟢 Robotics
🟡 JavaScript
🟡 Web Development
🔵 AI
```

---

# 🎯 My Goals

```text
☐ Professional Web Developer
☐ Advanced Python Developer
☐ Advanced C++ Developer
☐ AI Projects
☐ Smart Robots
☐ Mobile Applications
☐ Game Development
☐ Large GitHub Portfolio
```

---

# 🌟 Future Projects

```text
🤖 AI Robot
🚗 Autonomous Car
🏠 Smart Home
🎮 Mobile Game
🌐 Advanced Website
🧠 AI Assistant
📱 Mobile Application
🔐 Security Project
```

---

# 💭 My Philosophy

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=1000&color=00FF9D&center=true&vCenter=true&width=700&lines=Learn+%F0%9F%93%9A;Practice+%F0%9F%92%BB;Build+%F0%9F%9A%80;Test+%F0%9F%A7%AA;Improve+%F0%9F%94%A5;Never+Stop+Learning+%F0%9F%A7%A0"/>

</div>

---

# 🏆 My Vision

<div align="center">

<img src="https://media.giphy.com/media/MC6eSuC3yypCU/giphy.gif" width="400">

<h2>🚀 Learn • Create • Build • Improve</h2>

<h3>🤖 Robotics + 💻 Programming + 🎨 Design</h3>

</div>

---

# ❤️ Thanks for Visiting!

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2500&pause=700&color=FF4D6D&center=true&vCenter=true&width=650&lines=Thanks+for+visiting+my+GitHub!+%E2%9D%A4%EF%B8%8F;Keep+Coding+%F0%9F%92%BB;Keep+Learning+%F0%9F%93%9A;Keep+Building+%F0%9F%9A%80;Never+Give+Up+%F0%9F%94%A5"/>

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0072ff,100:00c6ff&height=120&section=footer"/>

</div>
