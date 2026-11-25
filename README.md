# Lewis Desforges

AI engineer: LLM evals, vision pipelines, on-device ML and the infrastructure under them. I build and ship AI-integrated products end to end, mostly on my own, from the model to the cloud it runs on.

Most of my work is closed source, so it is written up as case studies that say what each project is, how it works and where it stands today. The code I can make public is below.

- Site: [desforgeslabs.com](https://desforgeslabs.com)
- LinkedIn: [lewisdesforges](https://www.linkedin.com/in/lewisdesforges/)

## Case studies

- [Pothole Reporter](https://desforgeslabs.com/work/pothole-reporter.html): an Android app that finds potholes on the phone itself and helps the driver report each one to the right council. In development, road testing.
- [PixelOps](https://desforgeslabs.com/work/pixelops.html): a solo product suite for photographers, including an MCP bridge that lets Claude work in a Lightroom catalogue without being able to damage it. Live at pixelops.me; some tools in development.
- [MG-GPT](https://desforgeslabs.com/work/mg-gpt.html): a 51M-parameter GPT written from scratch in PyTorch and served from a CPU-only Lambda. Live demo; open source.

## Public repositories

- [mg-gpt](https://github.com/gitLRD/mg-gpt): the full MG-GPT stack, from forum scrape to training to a live chatbot on AWS Lambda. Written to be read.
- [Perch](https://github.com/gitLRD/Perch): a native macOS floating window that shows which Claude Code sessions are waiting on you.
- [blender-mcp](https://github.com/gitLRD/blender-mcp): a fork of [ahujasid/mcp-for-blender](https://github.com/ahujasid/mcp-for-blender) (BlenderMCP), which connects Claude to Blender through the Model Context Protocol. I use it. It is an unmodified fork; the code is the original author's.
