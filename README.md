

# RefCount - Visual Object Counter

Hello! 👋  
Welcome to the **RefCount** project. This tool helps you **count how many times an object appears** in an image by using just a reference crop. It's **scale-invariant** for now, meaning it works when the object changes size, but it’s **not rotationally invariant** yet. We’ll work on that later!

---

### 🚀 What’s it All About?

This is a **simple tool** to detect and count objects in images, without needing to train a model for each new object. You just crop the reference image (like a small piece of the object), and it finds and counts how many times that object appears in a test image. All you need is **one image of the object**, and you're good to go!

---

### 🎬 Demo

Here’s a quick demo of how the tool works.  


![Demo](assets/demo.gif)

---

### 🔧 How Does It Work?

Right now, it detects objects based on **scale**, meaning it works when the object changes size in different images. The idea is to crop a reference from one image, load another image, and then the tool will match that reference to all similar instances in the test image.

**Important:**  
The tool doesn't yet handle rotation. So, if the object is rotated in the image, it may not detect it well. But we plan to fix that soon! We’re working on making it **rotation-invariant** too.

---

### 🧠 Why Is It Useful?

In industries, there are **many different types of objects**, and training a model for every new object is **too difficult** and **time-consuming**. With this tool, you just need a **reference crop** from any object, and it can help count that object in new images, no matter where or how it's placed.

It’s a **lightweight solution** for industries that need to count or detect objects without complex training.

---

### 🚀 Future Plans

- Right now, it works for **scale-invariant detection** (size changes), but we will soon make it work for **rotation-invariant detection** as well.  
- Our long-term goal is to create a **deep learning-based model** that can detect any object from just a reference image, without needing training for each new object.  
- **Problem with training**: In industry, it’s very difficult to train models for every new object. This tool hopes to make that process **easier and faster**.

---

### 📧 Contact

If you’re interested or want to know more, feel free to shoot me an email at:  
**siddique2127@gmail.com**

---

### 🚧 More Updates Coming Soon!

This tool is still in its early stages, so expect updates and improvements soon! Stay tuned for more features.  

Thanks for checking it out! 🙏