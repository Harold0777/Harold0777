<h1 align="center">Haroldo Diógenes</h1>

<p align="center">
  Software Engineering student at IFCE · 2nd semester · Ceará, Brazil
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=c,python,js,html,css,git,github,linux" alt="Tech stack" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Algorithms-0A66C2?style=flat-square" alt="Focus: Algorithms" />
  <img src="https://img.shields.io/badge/Studying-Software%20Engineering-0A66C2?style=flat-square" alt="Studying Software Engineering" />
  <img src="https://img.shields.io/badge/English-Basic%2FIntermediate-2EA44F?style=flat-square" alt="English: Basic/Intermediate" />
  <img src="https://img.shields.io/badge/Open%20to-Open%20Source-8957E5?style=flat-square" alt="Open to Open Source" />
</p>

---

<table>
<tr>
<td width="50%" valign="top">

### About

I'm finishing my second semester of Software Engineering at IFCE (Federal Institute of Ceará, Brazil). I'm building a solid foundation in programming logic, algorithms, and software design. I mostly write C and Python, and I'm starting with web development.

</td>
<td width="50%" valign="top">

### Currently

- Learning data structures and algorithms
- Practicing C and Python
- Getting started with HTML, CSS, and JavaScript
- Learning Git and GitHub workflows
- Using Linux as my daily environment

</td>
</tr>
</table>

---

### Projects

- [**Heap Sort in C**](https://github.com/Harold0777/heap-sort-c): Heap Sort implementation with execution time benchmark on random, sorted, and reversed inputs

---

### A bit of code

From my [Heap Sort](https://github.com/Harold0777/heap-sort-c) project:

```c
// Keeps the max-heap property for the subtree rooted at index i
void heapify(int arr[], int n, int i) {
    int largest = i;
    int left = 2 * i + 1;
    int right = 2 * i + 2;

    if (left < n && arr[left] > arr[largest])
        largest = left;

    if (right < n && arr[right] > arr[largest])
        largest = right;

    if (largest != i) {
        int temp = arr[i];
        arr[i] = arr[largest];
        arr[largest] = temp;
        heapify(arr, n, largest);
    }
}
```

---

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Harold0777/Harold0777/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Harold0777/Harold0777/output/github-snake.svg" />
    <img alt="Snake animation eating my contribution graph" src="https://raw.githubusercontent.com/Harold0777/Harold0777/output/github-snake-dark.svg" />
  </picture>
</p>

<p align="center">
  <a href="mailto:diozharoldo634@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.instagram.com/haroldo_diogenes/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
</p>
