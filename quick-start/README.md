---
description: quick start to build mini lab env of MSA
cover: https://ubiqube.com/wp-content/uploads/Highlights-Documentation-768x839.png
coverY: 0
---

# Quick Start

### Required <a href="#required" id="required"></a>

* Docker
* Docker Compose
  * Higher than 1.29

{% hint style="info" %}
Windows Platform requires shell executable software like Git-Bash(MSYS)
{% endhint %}

### Download Mini Lab Source

download Mini Lab source from [https://github.com/ubiqube/quickstart](https://github.com/ubiqube/quickstart.git)

### Install Mini Lab

* Linux
  * execute ./scripts/[install.sh](https://github.com/ubiqube/quickstart/blob/master/scripts/install.sh)
  * **Note**:if script does not work well. execute sh as **root** user
* Windows
  * execute ./scripts/[install\_win.sh](https://github.com/ubiqube/quickstart/blob/master/scripts/install\_win.sh)
* Mac
  * Mod ./scripts/[install.sh](https://github.com/ubiqube/quickstart/blob/master/scripts/install.sh)
    * [line 331](https://github.com/ubiqube/quickstart/blob/master/scripts/install.sh#L331)
      * mod grep option **-P** to **-E** like\
        compose\_vers=$(docker-compose -v | **grep -oE** '\d+.\d+.\d+')
  * execute ./scripts/[install.sh](https://github.com/ubiqube/quickstart/blob/master/scripts/install.sh)****
