# Cars

<img src="images/logo.png" alt="Cars project logo" width="124">

An Angular car-rental demo with a filterable catalog and a booking enquiry form.

<img src="images/main-car.png" alt="Sports car from the project’s landing page" width="720">

## Run locally

The repository contains the compiled site. With Git and Python 3 installed, serve the checkout from its parent directory so the browser can resolve the build’s `/cars/` base path.

```sh
git clone https://github.com/khurik662/cars.git
python3 -m http.server --bind 127.0.0.1 8000
```

Open [http://127.0.0.1:8000/cars/](http://127.0.0.1:8000/cars/).

The catalog and filters depend on a third-party API. The booking form sends the selected car, name and phone number to that service. For a portfolio walkthrough, stop before submitting the form.

## How it works

| File | Role |
| --- | --- |
| `index.html` | HTML entry point with the `/cars/` base path |
| `main.js` | Compiled Angular application, catalog filters and enquiry form |
| `polyfills.js` | Browser compatibility bundle |
| `styles.css`, `images/` | Global styles and project artwork |

## Project history

The [initial upload](https://github.com/khurik662/cars/commit/e5194b42d8973843409b27c3e8ef1fd54c8c9be6) was committed on 26 April 2025. See [commit history](https://github.com/khurik662/cars/commits/main/) for subsequent changes.
