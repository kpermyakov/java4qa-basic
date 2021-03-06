# Базовый тренинг Intro to Java Applications for QA
Длительность 30 часов.
Рассматривается java-приложение как gray box. Небольшое введение в синатксис, но основной упор на внешнее поведение уже готового Java Application.
Участники обучаются на примере полу-готового java app, которое необходимо покрыть тестами и локализовать дефекты.
Цель: понимание работы уже написанного java app.

## Objectives
Участники после курса смогут:
- установить JDK и запустить java app
- собрать jar и исправить проблемы нахождения нужных jar (CNFE)
- локализовать compile-time ошибки и создать понятный разработчикам багрепорт
- локализовать runtime-ошибки и создать понятный разработчикам багрепорт
- локализовать и исправить своими силами ряд типовых runtime-ошибок приложения (NPE, IOE, SQLE)
- локализовать и исправить своими силами ряд типовых проблем с памятью (OOME, SOE, gc pauses)
- сформулировать ключевые граничные условия типового java app для создания тестов (сеть, IO, threads, heap, stack)
- профилировать и семплировать java app для выявления узких мест

## Java Installation
- Installation process demo
- Practice: JDK installation
- JDK structure demo
- JDK tools overview
## Java Application Structure
- App overview and structure
- Class
- Classpath
- Package
- JAR
- Practice: Java App compiling 
- Practice: Java App launching
- JVM options and App parameters
- Compiling and Running old version Apps
- Типовые граничные условия (для тестов)

## Java Code
- Build tools: mvn
- Class
- Method
- Call Stack
- Design
- Object
- Simple App demo

## Exceptions in Java
- Call stack recap
- try/catch/finally
- Exceptions hierarchy
- Mostly used exceptions
- Stacktrace in log demo

## Typical Server App Design
- threads
- sockets

## JVM Architecture
- Threads
- Stack
- Heap
- GC overview
- JVM options for heap and stack tuning
- JVisualVM demo
- Типовые граничные условия для тестов

## GC and Heap Architecture
- Garbage
- Heap architecture
- Types of GC
- GC and Heap tuning
- JVM options for GC tuning
- GC console demo
- Типовые граничные условия для тестов

## Heap and Stack Monitoring
- *Sampling vs Profiling*
- Heap and GC monitoring with JVisualVM demo
- Stack and threads monitoring with JVisualVM demo
- Heap and Stack Dumps with JVisualVM demo

## Java App Troubleshooting
- Main trouble reasons
- *Logging frameworks*
- Exceptions in logs
- JVM crash dumps
- GC collection pauses
- Типовые граничные условия для тестов

## Typical Enterprise App Architecture
- Layers: UI, BL, DAL
- Frameworks overview (Spring, EJB)
- JDBC
- AppServer architecture
- ThreadPools
- ConnectionPools
- Типовые граничные условия enterprise java app для тестов