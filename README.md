## Description

This repository contains scripts you will need to generate a PRD template.
It also contains a sample PRD under `samples/epfl-pocketcampus` for your reference.

>[!NOTE]
>As you may know, the EPFL Pocketcampus app was developed in the first iteration
>of this course. 

## Setup

1. Ensure you have python3 on your local machine. 
```
python3 --version
```

2. Create a Virtual Enviornment
```
pip3 install virtualenv
python3 -m virtualenv chimpagne_venv (is in gitignore)
```

4. Activate the Virtual Environment
```
source venv/bin/activate
```

5. Install the `prd_tools` python app
```
pip install -r requirements.txt
pip install -e .
```

## Usage

### Creating a PRD Template

1. Initialize a new PRD template
```
swent_prd init <optional: folder name>
```
If you do not pass a folder name, it will create a default folder called
`sections`. 

### Generating the PDF

1. Run the `generate` command
```
swent_prd generate  --team <TeamNumber> <folder name>
```

This will create a file called `Team_<Number>_prd.pdf` in the root folder.

>[!IMPORTANT]
> When you begin filling out the various sections, you should remove the
> comments added in italics. They are only there to help start your thinking
> process.
