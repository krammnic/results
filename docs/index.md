---
hide:
  - navigation
---

<style>
.md-content .md-typeset h1 { display: none; }
</style>

## Flash.it

**Flash.it** is a modern framework that provides powerful containers to accelerate your ML-infrastructure.

The key features are:

* **Fast**: Very high performance. You can get up to 40x speed up!
* **Intuitive**: It is obvious what to do in any situation.
* **Easy**: Designed to be easy to use. Put your service in container and you are almost done!
* **SOTA**: Only SOTAs!
* **Robust**: Get production-ready containers and MLOps for them.
* **Standards-based**: Container architecture is recommended by Nvidia!

[//]: # (## Opinions)

[//]: # ("_[...] I'm using **FastAPI** a ton these days. [...] I'm actually planning to use it for all of my team's **ML services at Microsoft**. Some of them are getting integrated into the core **Windows** product and some **Office** products._")

[//]: # ()

[//]: # (<div style="text-align: right; margin-right: 10%;">Kabir Khan - <strong>Microsoft</strong> <a href="https://github.com/tiangolo/fastapi/pull/26" target="_blank"><small>&#40;ref&#41;</small></a></div>)

[//]: # ()

[//]: # (---)

[//]: # ()

[//]: # ("_We adopted the **FastAPI** library to spawn a **REST** server that can be queried to obtain **predictions**. [for Ludwig]_")

[//]: # ()

[//]: # (<div style="text-align: right; margin-right: 10%;">Piero Molino, Yaroslav Dudin, and Sai Sumanth Miryala - <strong>Uber</strong> <a href="https://eng.uber.com/ludwig-v0-2/" target="_blank"><small>&#40;ref&#41;</small></a></div>)

[//]: # ()

[//]: # (---)

[//]: # ()

[//]: # ("_**Netflix** is pleased to announce the open-source release of our **crisis management** orchestration framework: **Dispatch**! [built with **FastAPI**]_")

[//]: # ()

[//]: # (<div style="text-align: right; margin-right: 10%;">Kevin Glisson, Marc Vilanova, Forest Monsen - <strong>Netflix</strong> <a href="https://netflixtechblog.com/introducing-dispatch-da4b8a2a8072" target="_blank"><small>&#40;ref&#41;</small></a></div>)

[//]: # ()

[//]: # (---)

[//]: # ()

[//]: # ("_I’m over the moon excited about **FastAPI**. It’s so fun!_")

[//]: # ()

[//]: # (<div style="text-align: right; margin-right: 10%;">Brian Okken - <strong><a href="https://pythonbytes.fm/episodes/show/123/time-to-right-the-py-wrongs?time_in_sec=855" target="_blank">Python Bytes</a> podcast host</strong> <a href="https://twitter.com/brianokken/status/1112220079972728832" target="_blank"><small>&#40;ref&#41;</small></a></div>)

[//]: # ()

[//]: # (---)

[//]: # ()

[//]: # ("_Honestly, what you've built looks super solid and polished. In many ways, it's what I wanted **Hug** to be - it's really inspiring to see someone build that._")

[//]: # ()

[//]: # (<div style="text-align: right; margin-right: 10%;">Timothy Crosley - <strong><a href="https://www.hug.rest/" target="_blank">Hug</a> creator</strong> <a href="https://news.ycombinator.com/item?id=19455465" target="_blank"><small>&#40;ref&#41;</small></a></div>)

[//]: # ()

[//]: # (---)

[//]: # ()

[//]: # ("_If you're looking to learn one **modern framework** for building REST APIs, check out **FastAPI** [...] It's fast, easy to use and easy to learn [...]_")

[//]: # ()

[//]: # ("_We've switched over to **FastAPI** for our **APIs** [...] I think you'll like it [...]_")

[//]: # ()

[//]: # (<div style="text-align: right; margin-right: 10%;">Ines Montani - Matthew Honnibal - <strong><a href="https://explosion.ai" target="_blank">Explosion AI</a> founders - <a href="https://spacy.io" target="_blank">spaCy</a> creators</strong> <a href="https://twitter.com/_inesmontani/status/1144173225322143744" target="_blank"><small>&#40;ref&#41;</small></a> - <a href="https://twitter.com/honnibal/status/1144031421859655680" target="_blank"><small>&#40;ref&#41;</small></a></div>)

[//]: # ()

[//]: # (---)

[//]: # ()

[//]: # ("_If anyone is looking to build a production Python API, I would highly recommend **FastAPI**. It is **beautifully designed**, **simple to use** and **highly scalable**, it has become a **key component** in our API first development strategy and is driving many automations and services such as our Virtual TAC Engineer._")

[//]: # ()

[//]: # (<div style="text-align: right; margin-right: 10%;">Deon Pillsbury - <strong>Cisco</strong> <a href="https://www.linkedin.com/posts/deonpillsbury_cisco-cx-python-activity-6963242628536487936-trAp/" target="_blank"><small>&#40;ref&#41;</small></a></div>)

[//]: # ()

[//]: # (---)

[//]: # ()

[//]: # (## **Typer**, the FastAPI of CLIs)

[//]: # ()

[//]: # (<a href="https://typer.tiangolo.com" target="_blank"><img src="https://typer.tiangolo.com/img/logo-margin/logo-margin-vector.svg" style="width: 20%;"></a>)

[//]: # ()

[//]: # (If you are building a <abbr title="Command Line Interface">CLI</abbr> app to be used in the terminal instead of a web API, check out <a href="https://typer.tiangolo.com/" class="external-link" target="_blank">**Typer**</a>.)

[//]: # ()

[//]: # (**Typer** is FastAPI's little sibling. And it's intended to be the **FastAPI of CLIs**. ⌨️ 🚀)

## Requirements

Python 3.10+

Flash.it stands on two main shoulders:

* <a href="https://huggingface.co/docs/transformers/index" class="external-link" target="_blank">Transformers</a>.
* Flash-formers: Our acceleration framework.

But actually you don't need to care about them. Just install executable!

## Resources

For newbie users we recommend to run on **Nvidia GPU** or **Groq LPU**. TPU or just CPU are possible but there are still **unstable**. You can read more about resources here.

**Important:** Cold run optimizations are possible only on **1 A100** or **better** setups!

## Installation

<div class="termy">

```console
$  curl https://flash.it.com/install/{YOUR TOKEN}
---> 100%
```

</div>

## Example

### Let's create LLama container!

* Run Flash.it executable, pass your token in it.

```
./flash.it --run
```

Web-CLI will be opened automatically on http://127.0.0.1:8000/containers/.

<img src="img/web-cli.png">

### Create container

Create it using web-cli or using command:

<div class="termy">

```console
./flash.it add --name llama-container  --model llama
```
</div>

### Set config

<i>**Intuition:**</i> Container need to now something about your service. **For instance:** model, metrics, params.

#### Using prompt

Open web-CLI. To generate config automatically you need to paste **README** or description of your service in field "**Set config prompt**":

<img src="img/set_config_prompt.png">

For this example prompt will be:

```commandline
Simple llama 7B params model project that only require 1 A100 GPU.
```

Then you will get **config.pkl** file. You can edit it and then set config using command:

```console
./flash.it set_config --llama-container --config.pkl
```

#### Standard way

Execute:

```console
./flash.it config -o .
```

You will get your current empty config. Fill it and set it to the container using command:

```console
./flash.it set_config --llama-container --config.pkl
```

In both ways you will end with something like:

```yaml
container {
  name = "llama-container"
  edit_code = "yes"
  path = "."
  model_path = "PATH_TO_LLAMA"
  predictor_path = "PATH_TO_LLAMA"
  start = "hot"
  doxegen = "no"
  id = 1234
  params = 7 // Only for LLMs
  data = "PATH_TO_DATA" // Might be important
  metric = 60
  push_custom = 0
  run_command = "python main.py"
  infrastructure_config {
    devops = "kubernetes"
    model = "llama"
    dockerfile = "basic"
    kuber = "basic"
    run_file = "."
  }
  resources {
    gpu = "1 A100"
    cpu = ""
    tpu = ""
    lpu = ""
    ram = ""
  }
  docs = "docs"
}
```

### More about config

Some fields of config that were provided above might be unusual. Here are some intuitions behind them:


1. `name = llama-container` Set the name of the container.
2. `edit_code = yes` Our containers usually need to change some code in order to optimize it.
3. `path = .` Path to your service.
4. `model_path = "PATH_TO_MODEL"` Path to your model.
5. `predictor_path = "PATH_TO_PREDICTOR"` Usually there might be some external predictor in LLMs. This field is not required
6. `start = hot` Flash.it has two modes: `cold` and `hot`. This modes primarily set's available time for optimizations. You can read more about them in ...
7. `doxegen = no` Flash.it can automatically generate docs for you container using LLMs.
8. `id = 1234` Unique id of your container. Primary key. 
9. `params = 7` Billions of params. Used to rate optimality of your model
10. `data = "PATH_TO_DATA"` For some optimizations data is required. It is not required but very convenient to have it. 
11. `metric = 60 / metrics { ... }` Same proposal as params field. Flash.it uses it to estimate optimality of your model.
12. `push_custom` Determines whether a custom model is used.
13. `run_command` Runs your service.
14. `infrastructure_config` A configuration describing your infrastructure.
    15. `devops` Determines the devops mode of your container
    16. `model` Your ML-model.
    17. `dockerfile` Determines Dockerfile's type. Basic stands for auto-generated. You can set your custom Dockerfiles
    18. `kuber` Same as `dockerfile`! Use either auto-generated, either your own.
    19. `run_file` Your service's entry point.
    19. `resources { ... }` Resources required to run your service.

This setup is actually standard, but powerful! If you need more, read about advanced configs here.

### Optimize, build and run your container.

After you set up your config, run the command that will optimize and build your container:

```console
./flash.it --build --optimize --name llama-container run
```

If build ended successful, congratulations! You have built your first container! Now you can deploy it on [Kubernetes](https://kubernetes.io/):

```console
./flash.it --name llama-container deploy
```