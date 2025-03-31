https://klandermans.github.io/dairy-clock/


# 🗣️ KISS Talking Clock ⏰  
*A Keep It Stupid and Simple experiment in browser-based speech & time awareness*

## What is this?

A hilariously simple, browser-based **talking clock**.  
Made with nothing but HTML5 + JavaScript — and the magic of your browser's built-in speech engine.  

It was developed as part of a prototype for a real-world test setup... but ultimately never used because the test environment turned out to be *way too noisy* for any kind of spoken output to work properly.

Still, it was a fun little side quest. This is that experiment, frozen in time.

## 💡 Why?

We needed a clock that would:
- Announce the time out loud at set intervals
- Require **zero setup**, no installations, no dependencies
- Be dead simple to run and adapt
- Run on any computer with a modern browser

So we made one. With JavaScript’s `speechSynthesis` API and a touch of creative stubbornness.

## 🧪 How it works

1. Open the HTML page in **any modern browser** (Chrome, Firefox, Edge, etc.)
2. The page shows a minimal clock interface
3. At regular intervals (e.g. every minute), it uses the browser’s speech engine to *say* the time aloud

That’s it. No backend. No fancy frameworks. Just a good old `<script>` tag and a voice.

## 🛠️ Tech Stack

- HTML5
- JavaScript (vanilla!)
- Web Speech API (`speechSynthesis`)
- A sense of humor

## 🚫 Why we didn't use it

Because... real life.

The test environment where we wanted to deploy this thing was:
- Echoey
- Busy
- Full of people and machines making unpredictable noise

So the voice became background noise, and the usefulness of the talking clock kind of evaporated.

But hey — it *does* work! Just maybe not in a factory hall full of forklifts and yelling researchers.

## 🎉 What’s next?

Honestly, probably nothing.  
But if **you** want to build on this:
- Add voice settings
- Let users pick their language
- Add alarms, reminders, or even weather updates
- Hook it up to sensors or buttons

… go wild.

## 📷 Screenshot

![Screenshot of the talking clock interface](screenshot.png)  
*(Note: it looks extremely basic. That’s the point.)*

## 🧘 Philosophy

> "Keep it stupid and simple."  
> Not every tool needs a React frontend, a cloud backend, and ten microservices.  
> Sometimes, all you need is a browser and an idea.

## 📄 License

MIT — do whatever you like. Just don’t blame me if your coworkers get annoyed at your computer yelling the time every 60 seconds.

---

**Built by accident. Shared with love.**
