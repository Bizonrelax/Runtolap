# Runtolap

A formal mathematical preprint presenting a complete proof of the **Lonely Runner Conjecture** using a novel framework based on **Rational Rank Reduction** and modular torus endomorphisms.

## Project Status

*   **Type:** Independent Research / Mathematical Preprint
*   **License:** [The Unlicense](LICENSE) (Public Domain Dedication)
*   **Axiomatic Basis:** Algebraic Geometry of Numbers, Kronecker's Approximation Theorem, and Modular Diophantine Equations.

---

## About the Method

The classical approach to the Lonely Runner Conjecture typically relies on induction by the total number of runners $n$. However, this method routinely fails due to dimensional preservation during fractional rescaling. 

The **Runtolap** project bypasses this fundamental barrier by establishing a rigorous induction on the **rational rank $r$** of the relative velocity vector:

1.  **Global LCM Reduction:** The general continuous framework is partitioned into a system of localized trajectories on the torus based on minimal least common multiples.
2.  **Rational Rank Induction ($r \implies r+1$):** Trajectory closures are mapped to a smooth embedded subtorus $\mathbb{T}^r$. Applying Kronecker's theorem, we isolate a dependent layer and reduce the remaining degrees of freedom to a 1-dimensional discrete fiber.
3.  **Cyclic Ring Resolution ($r=1$):** The base of the induction collapses into a finite residue ring $\mathbb{Z}_p$. The existence of unblocked coordinates is firmly guaranteed via the modular Pigeonhole Principle combined with global structural LCM boundary constraints (resolving small-parameter anomalies for $n=3$ and $n=4$).

## File Structure

*   `proof.md` — The complete mathematical proof with full vector notations and anomaly resolutions (English and Russian versions available).
*   `LICENSE` — The standard text of **The Unlicense** dedicated to the public domain.

---

## Описание проекта (Russian Version)

**Runtolap** — это математический препринт, содержащий полное доказательство **Гипотезы об одиноком бегуне (Lonely Runner Conjecture)** с использованием принципиально нового подхода, основанного на **редукции рационального ранга** и модулярных эндоморфизмах тора.

### Суть метода

Традиционные попытки штурма гипотезы через индукцию по числу бегунов $n$ заходили в тупик из-за неизменности размерности системы при масштабировании долей через НОД. В рамках данного проекта индукция перенесена на **рациональный ранг $r$** вектора относительных скоростей:

1.  **Глобальная НОК-редукция:** Непрерывный случай сводится к локализованным траекториям на торе через минимальные наборы наименьших общих кратных.
2.  **Индукция по рангу ($r \implies r+1$):** Замыкания траекторий отображаются на гладкий подтор $\mathbb{T}^r$. С помощью теоремы Кронекера выделяется зависимый слой, что сокращает оставшиеся степени свободы до одномерного дискретного фибера.
3.  **Разрешение циклической базы ($r=1$):** База индукции сводится к конечному кольцу вычетов $\mathbb{Z}_p$, где наличие незаблокированных точек строго доказывается модульным принципом Дирихле и структурными ограничениями (с полной зачисткой аномалий малых параметров для $n=3$ и $n=4$).
