# COMP3710_DEMO1
COMP3710 DEMONSTRATION 1 FRACTALS
# Sierpinski Triangle Fractal (PyTorch)

## 📌 Overview
This project implements the **Sierpinski Triangle** fractal using **PyTorch**.  
The Sierpinski Triangle is a famous fractal discovered by Polish mathematician **Wacław Sierpiński**.  
It is formed by repeatedly removing the middle triangle from a larger equilateral triangle, creating a **self-similar** pattern.

Unlike Mandelbrot/Julia fractals, which are based on complex numbers, the Sierpinski Triangle is a **geometric fractal**.  
In this implementation, PyTorch tensors and GPU parallelism are used to compute the fractal efficiently.

<img width="699" height="672" alt="image" src="https://github.com/user-attachments/assets/5004e95f-8f9c-416b-a8ae-c50d2cdd4ca0" />


---

## 🚀 How it Works
- A grid of coordinates `(x, y)` is generated using `torch.meshgrid`.  
- The fractal pattern is defined by a simple **bitwise rule**:

📚 References

Sierpinski Triangle (Wikipedia)

PyTorch Documentation
