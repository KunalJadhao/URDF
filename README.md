
# 🛠️ My 4-Wheel Robot URDF

A simple **4-wheeled differential drive robot** model created using **URDF** (Unified Robot Description Format) for ROS/ROS2 simulations.  
This robot is designed for use in **RViz** and **Gazebo** for visualization, navigation experiments, and robotics learning.

---

## 📷 Preview

(<img width="1920" height="1200" alt="Screenshot from 2025-08-08 10-49-08" src="https://github.com/user-attachments/assets/e067efe0-5d8f-456a-80ff-110cdb90de6f" />
)
(<img width="1920" height="1200" alt="Screenshot from 2025-08-08 10-49-16" src="https://github.com/user-attachments/assets/7cdbbdf5-45b4-4dfd-86f8-1937013e560f" />
)

<img width="1920" height="1200" alt="Screenshot from 2025-08-08 10-49-23" src="https://github.com/user-attachments/assets/874e528c-575f-42e0-ab78-354df1e549e7" />


<img width="1920" height="1200" alt="Screenshot from 2025-08-08 10-51-18" src="https://github.com/user-attachments/assets/80a46387-44c6-463c-a1c0-287772f0e609" />


<img width="1920" height="1200" alt="Screenshot from 2025-08-08 10-56-40" src="https://github.com/user-attachments/assets/d435140e-a334-4315-8763-d818519d6d92" />


---

## 📂 Project Structure

```

urdf_tutorial/
│
├── urdf/
│   └── my_robot.urdf        # The main URDF file for the robot

## ⚙️ Robot Features

* ✅ 4-wheeled differential drive layout
* ✅ Continuous joints for wheel rotation
* ✅ Realistic wheel positions for simulation
* ✅ Uses `base_footprint` for proper localization in ROS
* ✅ Materials and colors for better visualization

---

## 🖼️ Adding Your Own Screenshots

1. Run the robot in RViz or Gazebo.
2. Take screenshots from **front** and **side** angles.
3. Save them into the `images` folder as `front_view.png` and `side_view.png`.
4. Git will automatically show them in this README.

Example:

```bash
mkdir images
mv ~/Pictures/front_view.png images/
mv ~/Pictures/side_view.png images/
```

---

## 🛠️ Customization

You can modify:

* **Wheel size** → change `radius` and `length` in `<cylinder>`
* **Base size** → edit `<box size="x y z"/>`
* **Colors** → change `<material>` RGBA values
* **Wheel positions** → adjust `xyz` in `<origin>`

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).

---

💡 *If you like this project, give it a ⭐ on GitHub to support my work!*

```

---

If you want, I can also give you **ready-made example images** with a transparent background so your GitHub page looks clean until you take your own screenshots.  

Do you want me to prepare those sample images for you now?
```
