# TurboChat Rails

Application developed in the Real Seguro Viagem passport challenge. The application utilizes Turbo and Stimulus to enhance the user experience, Devise for user authentication, and Tailwind CSS along with DaisyUI for styling.

## Features

The application includes the following features:

- User authentication with Devise: Users can register, log in, and log out of the application.
- Creation and management of chat groups: Users can create chat groups, add members to existing groups, and manage group settings.
- Real-time chat: Group members can send real-time messages and see messages from other members updated automatically.
- Styling with Tailwind CSS and DaisyUI: The application interface is styled using Tailwind CSS, a utility CSS framework, with the assistance of DaisyUI to add pre-styled components.

## System Requirements

Make sure you have the following dependencies installed on your system:

- Ruby 3.1.3 or higher
- Rails 7.0.5 or higher
- Database (such as sqlite)

## Environment Setup

Follow these steps to set up the application environment:

1. Clone this repository to your local machine.
2. Navigate to the application directory.

```bash
cd railschat
```

3. Install Ruby dependencies by running the command:

```bash
bundle install
```

4. Create and migrate the database:

```bash
rails db:create
rails db:migrate
```

6. Start the local server:

```bash
rails s
```

The application will be available at `http://localhost:3000`.

## Usage

1. Access the homepage in your browser.
2. Create an account or log in if you already have an existing account.
3. Create a new chat group or join an existing group.
4. In the chat group, you can send messages and see messages from other group members.
