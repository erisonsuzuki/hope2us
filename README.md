# Hope2Us

Hope2Us is a web application built with Ruby on Rails that facilitates the donation of items. Users can register, create donation listings, and view the status of their contributions. Administrators have a dedicated dashboard to manage donation items and approve incoming donations, ensuring a smooth and transparent process for all participants.

## Features

- **User Authentication:** Secure sign-up and login functionality for donors.
- **Donation Management:** Users can create, view, and track their donations.
- **Admin Dashboard:** Administrators can manage donation items and approve contributions.
- **Status Tracking:** Donations are tracked through various stages, including `pending_receipt`, `waiting_approval`, `approved`, `confirmed`, and `canceled`.

## Technologies

- **Backend:** Ruby on Rails
- **Database:** PostgreSQL (or as configured in `config/database.yml`)
- **Authentication:** Devise

## Getting Started

### Prerequisites

- Ruby
- Rails
- Bundler
- PostgreSQL (or another relational database)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/erisonsuzuki/hope2us.git
   cd hope2us
   ```

2. **Install dependencies:**
   ```bash
   bundle install
   ```

3. **Set up the database:**
   ```bash
   rails db:create
   rails db:migrate
   rails db:seed
   ```

4. **Run the application:**
   ```bash
   rails server
   ```

The application will be available at `http://localhost:3000`.

## Usage

### Users

- **Sign up:** Create a new account to start donating.
- **Create a donation:** Fill out the donation form with the required details.
- **View donations:** Check the status of your donations in your profile.

### Administrators

- **Log in:** Access the admin dashboard at `/admin`.
- **Manage items:** Add, edit, or remove donation items.
- **Approve donations:** Review and approve pending donations.
