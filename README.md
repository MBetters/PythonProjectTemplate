# My Python Project Template

I'm using pipenv (<https://pipenv.readthedocs.io/en/latest/>) to manage dependencies. After installing pipenv, run `pipenv install --skip-lock` in this directory to install the dependencies. This template includes the dependencies I typically use.

After cloning this repo, rename the directory to whatever you want. Let's say you call it `myproject`.

To setup Jupyter, run...

```bash
pipenv shell
python -m ipykernel install --user --name=myproject
```

Give the `serve.sh` script execute permissions by running `chmod +x serve.sh`. To serve the Jupyter notebook, run...

```bash
pipenv shell
./serve.sh localhost 8888
```

... then go to the URL it spits out, click `New` --> `myproject` and start coding!

