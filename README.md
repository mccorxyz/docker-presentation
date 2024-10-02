# Docker Presentation

Here lies the Docker presentation that I gave in September 2024 to the University of Minnesota Duluth ACM club.

The presentation is written in markdown and can be easily rendered if you utilize the recommended extensions in the `.vscode` directory.

The presentation is far from all encompasing. At times we went off on tangents and pointed out specifics as we tackled each demo.

## Running the demos

I've added a `playbook.md` file to the root of each demo directory. It explains the demo, the value of the demo, and the commands necessary to try the demo for yourself.

### Demo Five

Demo five involves me spinning up the ELK-stack, which is a stack for storing and searching your software logs.

I used [this repository](https://github.com/deviantony/docker-elk/tree/release-7.x?tab=readme-ov-file#default-kibana-index-pattern-creation) as the baseline for that demo.

We then used a simple console application to quickly populate the stack with some logs to show how easy it is to quickly spin up many services and immediately benefit from them.
