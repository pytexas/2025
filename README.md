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
3. Pip install mkdocs material
    ```
    pip install mkdocs-material
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
