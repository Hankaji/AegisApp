
## 📋 Requirements

> ⚠️ **Important Note**
>
> This repo is a container repository that uses submodules of other github repositories and a part of an MVP system. For the best experience, it is recommended to run all 3 systems altogether:
>
> - 📱 [Frontend](https://github.com/Hankaji/GDGDoc-Aegis-Frontend) – Recommended for full functionality and UI interactions testing
> - 🖥️ [Backend](https://github.com/DankoFox/aegis-backend) – Required Backend Operations
> - 🧠 [AI](https://github.com/nmquan1/aegis-pipeline) - Require for some features such as auto-tagging
>
> Ensure that the backend, frontend, and AI pipeline can communicate over the same local network.

---

## ⚙️ Setup Instructions

Follow these step-by-step instructions to get the pipeline up and running on your machine.

### Clone the Repository

📥 Clone the repository to your local machine using `git`:
```bash
git clone https://github.com/Hankaji/AegisApp.git AegisApp
cd AegisApp
```
This will download the project and navigate you into its directory.

### Initialize submodules

```bash
git submodule init
```
This tell Git to prepare the submodules.

### Update Submodules (Fetch and Checkout)

```bash
git submodule update
```
This command will initialize and update the submodules.


### Working with Submodules

```bash
cd <submodule>
```
Each submodule will reside in its own directory within this repository. You can navigate into these directories to work on them.

A detail instruction on how to setup these systems are already well documented it their own repositories, please check the [Frontend](https://github.com/Hankaji/GDGDoc-Aegis-Frontend), [Backend](https://github.com/DankoFox/aegis-backend) and [AI](https://github.com/nmquan1/aegis-pipeline).
