# TCP Timing Lab Series
A measurement-driven exploration of TCP timing: from serialization delay to packet train, ACK clock, and throughput dynamics — making the invisible visible.

---

## 🌐 Global Topic Map

<p align="center">
  <img src="./images/tcp-timing-lab-topic-map.svg" width="100%">
</p>

> From **Serialization Delay (Δt = L/R)**
> to **Throughput Illusion**
> to **ACK Clock**
> to **TCP Behavior**

---

## 🧠 Core Idea

> **The network is not about rate — it is about time structure.**
>
> What we call “throughput” is only a *result*.
> What really governs the system is **timing**.

---

## 🔬 Labs

### 🟢 Phase ① — Physical Reality (Wire Time)

* **Lab01 — Serialization Delay (Δt = L/R)**
  👉 https://github.com/comeryu-max/tcp-timing-lab-01-serialization-delay
  *Observe the physical emission of bits on the wire*

---

### 🟡 Phase ② — Illusion vs Reality

* **Lab02 — Throughput Illusion**
  👉 https://github.com/comeryu-max/tcp-timing-lab-02-throughput-illusion
  *Throughput collapses, but Δt never changes*

---

### 🔵 Phase ③ — Hidden Clock

* **Lab03 — ACK Clock (Self-Clocking)** *(coming)*
  *TCP is not rate-controlled — it is ACK-driven*

---

### 🟣 Phase ④ — Disorder & Recovery

* **Lab04 — Retransmission Myth** *(coming)*
* **Lab05 — Retransmission Patterns** *(coming)*

---

### 🟠 Phase ⑤ — Semantics & Limits

* **Lab06 — ACK Semantics** *(coming)*
* **Lab07 — BDP / Window / Throughput** *(coming)*
* **Lab08 — Zero Window & Flow Control Collapse** *(coming)*

---

## 🔁 The Unified Model

```
Serialization (Δt = L/R)
        ↓
Packet Train (Continuity)
        ↓
ACK Clock (Timing Feedback)
        ↓
Throughput (Emergent Behavior)
        ↓
TCP Dynamics (Control System)
```

---

## 🔍 Why This Matters

Most network analysis focuses on:

* Bandwidth
* Throughput
* Packet loss

But these are **symptoms**.

This lab series shows that:

> ❗ The real system is a **time-structured feedback loop**

---

## ⚡ Engineering Principles

| Principle              | Meaning                    |
| ---------------------- | -------------------------- |
| Observe every packet   | Make the invisible visible |
| Measure every interval | Turn time into data        |
| Trust the packet       | Reality is on the wire     |
| Respect time structure | TCP lives in timing        |

---

## 🧭 Philosophy

> TCP is not complex because the world is orderly;
> it is complex because the world is habitually chaotic.
>
> We study it to **find causality within time**.

---

## 🔗 Topics

```
tcp-timing
packet-timing
serialization-delay
ack-clock
throughput-analysis
networking
wireshark
```

---

## 🏁 Final Thought

> From **L/R** to **ACK Clock**,
> from **packet spacing** to **system behavior**,
>
> this is a journey to reveal:

> 🔥 **The physical clock of TCP**

---
