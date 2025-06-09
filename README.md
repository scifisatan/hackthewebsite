# Hack the Circle: Khwopa 2024

Welcome to the Hack the Circle: Khwopa 2024 hackathon page! This project is designed to be composable and easily customizable. Below are the instructions on how to set up, configure, and customize the hackathon page.

## Table of Contents

- [Installation](#installation)
- [Customization](#customization)
- [Email Integration](#email-integration)
- [Running the Project](#running-the-project)

## Installation

First, clone the repository and install the dependencies:

```sh
git clone https://github.com/scifisatan/hackwebsite.git
cd hackwebsite
npm install
```

## Customization

### Data File

The hackathon page is highly composable and can be customized by editing the `data.ts` file located in the `src` directory. This file contains all the configurable data for the hackathon, including themes, event details, FAQs, and social media links.

### Example

Here is an example of how to customize the registration link in the `data.ts` file:

```tsx
import { Theme, Event, FAQ, Links } from "@/types";

export const targetDate = "2024-11-15T00:00:00";
export const registrationLink = "https://example.com/register";
export const learnMoreLink = "https://example.com/learn-more";
```

## Running the Project

To run the project locally, use the following command:

```sh
npm run dev
```

This will start the development server, and you can view the hackathon page at `http://localhost:5173`.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

---

Happy hacking!
