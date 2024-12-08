---
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages  # Use 'pages' widget to display a list of pages
headless: true
weight: 30  # Control the order of this section on the page

title: Latest News  # Section title
subtitle:  # Optional subtitle

content:
  count: 5  # Limit the number of items displayed to 5
  filters:
    author: ""  # You can filter posts by author if desired
    category: ""  # Filter by category, leave empty for all
    exclude_featured: false  # Do not exclude featured posts
    publication_type: ""  # Filter by publication type, leave empty for all
    tag: ""  # Filter by tag, leave empty for all
  offset: 0  # Start from the first post
  order: desc  # Order posts by most recent first
  page_type: post  # Display posts, not pages

design:
  view: 1  # View layout: '1' indicates default or a specific view
  columns: "1"  # Number of columns for the layout, here it's set to 1
---