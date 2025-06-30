
👇 **Here is your README file content:**

---

````
# AI Perfume Image Generator

---

## 🧩 About This Project

This project uses **Stable Diffusion v1.5** to generate realistic, high-resolution perfume bottle images from text prompts.

It includes:
✅ A Gradio web app
✅ Colab Notebook
✅ Example images
✅ Prompt Library

---

## 🚀 How to Use

### A. Run the Colab Notebook

1️⃣ Open the Colab Notebook:  
`AI_Perfume_Generator_Colab_Notebook.ipynb`

2️⃣ Run installation cells to set up dependencies:
```python
!pip install diffusers transformers accelerate safetensors gradio
````

3️⃣ Load the model checkpoint:

```python
from diffusers import StableDiffusionPipeline
import torch

model_id = "runwayml/stable-diffusion-v1-5"

pipe = StableDiffusionPipeline.from_pretrained(
    model_id,
    torch_dtype=torch.float16
).to("cuda")
```

4️⃣ Launch the Gradio interface:

```python
iface.launch(share=True)
```

5️⃣ Use the generated public link to access your app.

---

### B. Using the Gradio App

✅ Enter your prompt in the input field
✅ Click **Submit**
✅ The generated image will appear below
✅ Right-click to save the image

---

## 📂 Project Files Included

* README
* Prompt Library Excel file
* Portfolio of 20 images
* Showcase PDF (optional)
* Colab Notebook

---

## 💡 Example Prompts

* Luxury perfume bottle on a marble background, soft lighting
* Minimal perfume bottle on a white pedestal
* Perfume bottle surrounded by flowers, romantic lighting

---

## 🌐 Author & Contact

Prashant Wagh
prashantwagh2009@gmail.com

```

---

✅ **How to create the file:**
1. Copy all the text above.
2. Open Notepad (Windows) or TextEdit (Mac).
3. Paste the text.
4. **Save As:**
```

README\_AI\_Perfume\_Generator.txt

```
or
```

README\_AI\_Perfume\_Generator.md

```
(*If you want Markdown formatting.*)

✅ Done—this file is ready to attach to your project zip or share with clients.

---

If you **really prefer me to create and host a ready-to-download file**, just let me know—I’ll generate it via a temporary hosting link for you. 🌟
```
