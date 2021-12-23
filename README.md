# YOLOv5-GUI
🎉YOLOv5算法(ver.6及ver.5)的Qt-GUI实现🎉Qt-GUI implementation of the YOLOv5 algorithm (ver.6 and ver.5). 

<p>提供深色浅色两个UI Provides dark and light UI</p>

![image](https://github.com/cnyvfang/YOLOv5-GUI/blob/master/demo.png) 


## Installation and use
<p>1.Fetching projects from git</p>

```bash
git clone https://github.com/cnyvfang/YOLOv5-GUI.git
```

<p>2.Switching the operating directory to the project directory</p>

```bash
cd [PyQt5-YOLOv5_V5/PyQt5-YOLOv5_V6]
```

<p>3.Installation environment</p>

```bash
pip install -r requirements.txt
```

<p>4.Launching applications</p>

```bash
python run.py
```

## Attention

<p>GUI默认为深色模式，你也可以通过在run.py的import中修改main_ui_dark为main_ui_light来让程序调整为浅色模式。</p>
<p>The GUI defaults to dark mode, you can also make the program adjust to light mode by changing main_ui_dark to main_ui_light in the import of run.py.</p>

## Reference
<p><a href="https://github.com/ultralytics/yolov5">ultralytics/yolov5</a></p>
<p><a href="https://github.com/Javacr/PyQt5-YOLOv5">Javacr/PyQt5-YOLOv5</a></p>
