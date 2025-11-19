# Portfolio

A personal portfolio website built with Jekyll.

## Setup

### Prerequisites
- Ruby (version 2.7 or higher)
- Bundler (`gem install bundler`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mkatedes/Portfolio.git
   cd Portfolio
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Run the development server:
   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser and navigate to `http://localhost:4000`

## Configuration

The main configuration file is `_config.yml`. You can customize:
- Site title and description
- Email and URL
- Theme settings
- Plugins

## Project Structure

```
Portfolio/
├── _config.yml          # Jekyll configuration
├── _layouts/            # Layout templates
│   └── default.html
├── _includes/           # Reusable components
├── assets/              # CSS, JS, images
├── index.html           # Home page
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```

## Deployment

### GitHub Pages
1. Push your code to GitHub
2. Go to repository Settings > Pages
3. Select the branch to deploy (usually `main`)
4. Your site will be available at `https://your-username.github.io/Portfolio/`

## Customization

- Edit `_config.yml` to update site settings
- Modify `index.html` to change the home page content
- Create new pages in the root directory
- Add custom styles in `assets/css/style.css`

## License

This project is open source and available under the MIT License.