# Lecture 2 – Goals of OS & Types of OS → Important Questions

---

## Q1. What is the goal of maximum CPU utilization?

**Teri Language Answer:**
OS chahta hai ki CPU ek second bhi free na baitha rahe. Jaise factory me machine hamesha kaam kare bina rukhe.

**English Answer:**
The goal of maximum CPU utilization is to ensure the CPU is always busy and never idle. This improves overall system performance.

**Example (Teri language):**
Kitchen me chef ko ingredients milte rahe to vo nonstop cooking karega. Agar koi delay ho gaya, chef free ho gaya = CPU waste.

**Example (English):**
In a kitchen, if a chef keeps getting ingredients (data), he stays productive. OS tries to keep CPU in the same state — always working.

---

## Q2. What is process starvation? How does OS reduce it?

**Teri Language Answer:**
Starvation tab hoti hai jab koi chhoti file ya low-priority process kabhi chal hi nahi pati, bas wait karti rahti hai.

**English Answer:**
Process starvation occurs when a process waits too long to get CPU time because other processes are continuously prioritized over it.

**Example (Teri language):**
Movie ticket counter pe VIP logon ko hi ticket mile, to aam aadmi kabhi andar nahi ja payega — wahi starvation hai.

**Example (English):**
At a ticket counter, if only VIPs get service and normal people keep waiting, it's starvation. OS aims to avoid this.

---

## Q3. Why is higher priority job execution important in OS?

**Teri Language Answer:**
Agar koi kaam urgent hai, jaise accident patient, to uska kaam pehle hona chahiye — chhoti dikkat baad me dekhenge.

**English Answer:**
The OS must execute high-priority jobs first to ensure time-sensitive or critical tasks are not delayed.

**Example (Teri language):**
Hospital me fever wala baad me dekha jayega, lekin accident patient ka treatment pehle hoga.

**Example (English):**
In a hospital, a patient with fever waits, but a critical accident case gets immediate attention. OS handles priority similarly.

---

## Q4. What is a Single Process Operating System?

**Teri Language Answer:**
Ek time pe sirf ek kaam — dusra kaam tab tak rukta hai jab tak pehla pura na ho jaye.

**English Answer:**
A single process OS executes only one process at a time. It does not support multitasking.

**Example (Teri language):**
Jaise typewriter pe sirf ek letter likh sakte ho — doosra tabhi jab pehla khatam ho.

**Example (English):**
MS-DOS — only one program runs at a time, others must wait.

---

## Q5. How does Batch Processing OS work?

**Teri Language Answer:**
Kaam (job) pehle se likh ke operator ko diya jata hai. Operator sab kaam ek group me lagata hai aur ek saath chalata hai.

**English Answer:**
Batch processing OS collects jobs, groups similar ones into batches, and processes each batch one by one.

**Example (Teri language):**
Laundry shop me sab kapde ek hi baar machine me daale jaate hain — batch me.

 **Example (English):**
Users submit jobs, operator groups them, and processor runs each batch — like laundry in batches.

---

## Q6. What is a Multiprogramming OS?

**Teri Language Answer:**
Agar ek kaam ruk gaya (I/O), to CPU doosre kaam me lag jaata hai — isse CPU waste nahi hota.

**English Answer:**
Multiprogramming OS keeps multiple jobs in memory. If one job waits for I/O, CPU switches to another.

**Example (Teri language):**
Cooker chadhake tu chai banana start kar de — dono ka kaam ek time me ho raha hai.

**Example (English):**
While one task waits (e.g., video render), CPU does another (e.g., file copy).

---

##  Q7. What is Multitasking OS?

 **Teri Language Answer:**
User ko lagta hai sab kaam ek saath ho raha hai — WhatsApp, song, download sab chalu.

 **English Answer:**
Multitasking OS allows running multiple tasks by rapidly switching between them using time-sharing.

 **Example (Teri language):**
Mobile me ek hi time me call bhi aa raha hai, game bhi chal raha hai, aur song bhi.

 **Example (English):**
On your phone, you can chat, listen to music, and download files simultaneously — that's multitasking.

---

##  Q8. What is Multiprocessing OS?

 **Teri Language Answer:**
Ek computer me 2-3 CPU hote hain, har ek alag kaam karta hai — speed zyada, risk kam.

 **English Answer:**
Multiprocessing OS uses two or more CPUs in a single system to execute multiple processes in parallel.

 **Example (Teri language):**
3 chefs kitchen me alag alag dishes bana rahe hain — kaam jaldi hota hai, ek ruk gaya to doosra sambhal lega.

 **Example (English):**
Gaming PC with multiple processors — if one fails, others continue working.

---

##  Q9. What is a Distributed Operating System?

**Teri Language Answer:**
Alag alag computers milke kaam karte hain, lekin user ko lagta hai ek hi system hai.

**English Answer:**
Distributed OS manages a group of connected computers to act as a single system for users.

 **Example (Teri language):**
Hotel me kitchen alag, billing alag, service alag — sab ek hi system jaisa lagta hai.

**Example (English):**
Google search — data comes from different servers, but user sees one result page.

---

##  Q10. What is a Real-Time Operating System (RTOS)?

 **Teri Language Answer:**
Kaam fixed time me hona chahiye — delay allowed nahi, warna system fail.

 **English Answer:**
RTOS executes tasks within strict time constraints — used in critical systems where timing is crucial.

 **Example (Teri language):**
Missile launch ya robot control — ek second bhi delay hua to gadbad.

**Example (English):**
Used in air traffic control, medical monitors, manufacturing robots.

---

##  Extra: Common Question

### Q11. Difference between Multiprogramming Multitasking  and Multiprocessing

| Feature   | Multiprogramming | Multitasking    | Multiprocessing    |
| --------- | ---------------- | --------------- | ------------------ |
| CPU Count | 1                | 1               | 2 or more          |
| Purpose   | CPU idle na ho   | User feel fast  | High performance   |
| Example   | Cooker + chai    | WhatsApp + song | Gaming PC, servers |
