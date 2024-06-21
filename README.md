# PyTexas Conference 2025 Website

## Development
1. Create a virtual environment
    ```
    python -m venv venv
    ```
2. Activate virtual environment
    ```
    source venv/bin/activate
    ```
3. Pip install requirements
    ```
    pip install -r requirements.txt
    ```
4. Run dev server
    ```
    mkdocs serve
    ```

## Adding Announcement Banners
1. Add the following lines and update the text to `overrides/main.html`
```html
{% block announce %}
    <p>Attend the <a href="https://conference.pytexas.org">PyTexas 2025 Conference</a> April 11 - 13, 2025</p>
{% endblock %}
```

## Updating dependencies for Dependabot alerts
1. Edit constraints.txt to add or update any library version constraints.
2. Compile the `requirements.in` with `constraints.txt` to generate a version locked `requirements.txt` file.
   If using `uv`:
   ```
   uv pip compile requirements.in -c constraints.txt -o requirements.txt
   ```
   If using `pip-tools`:
   ```
   pip compile requirements.in -c constraints.txt -o requirements.txt
   ```
3. Commit the changed `requirements.txt` and log a Pull Request.
