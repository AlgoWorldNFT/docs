# Setting up local development

To start the project locally:

### 1. Create virtual environment for python functions:

```bash
python -m venv .venv
source .venv/bin/activate
```

### 2. Install all dependencies

```bash
pip install -r api/swappers/requirements.txt
```

### 3. Run the client locally:

```bash
vercel dev
```

Open `http://localhost:3000` with your browser to see the result.

> Running `vercel dev` for the first time will prompt you to setup and link with your existing/new vercel project. You can create a dummy project and link it to be able to run the development locally.
