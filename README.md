# VynzoraGGI

VynzoraGGI is a Django project for a relationship-focused service, designed to grow into a responsive website, desktop experience, and mobile apps.

## Current first step

The project currently includes a public landing page, a Django `core` app, and PostgreSQL-ready settings. The page introduces the service, its intended age threshold, privacy principles, safety approach, and the planned guided registration journey. Registration, identity checks, matching, and paid services are not implemented yet.

## Run locally

1. Create and activate a virtual environment.
2. Install dependencies with `python -m pip install -r requirements.txt`.
3. Copy `.env.example` to `.env`, then set your PostgreSQL password in `.env`. Create a PostgreSQL database named `vynzoraggi`.
4. Run `python manage.py migrate` and `python manage.py runserver`.
5. Open `http://127.0.0.1:8000/`.

## Planned build sequence

1. Public website and project foundation (current).
2. Guided registration with date of birth, age eligibility, username, private legal name, password, and clear terms consent.
3. Identity and profile-photo verification flow, designed to minimize storage and access to sensitive documents.
4. Profiles, preferences, discovery, matching, messaging, reporting, and moderation.
5. Premium plans and payment integration after eligibility and service rules are finalized.
6. Mobile and desktop clients backed by the same Django API.

Product rules such as age bands, premium eligibility, and age/sex-specific restrictions should be settled before those rules are encoded. Verification and payment processing also need a provider and privacy policy before launch.
