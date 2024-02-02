# HTML element
- **DOCTYPE**: declares exactly what it is, an HTML document.
- **lang**: notes what the language of the document. Helps assist search engines & browsers.
- The head tag holds all of our meta data for the document. 
- This holds various information such as the title of the document, viewport settings, and links to other files, such as CSS.

# Head element
  - **charset**: defines which characters are available, such as 0-9, A-Z, and symbols.
      - UTF-8 covers almost all of the characters
  - **http-equiv**: Allows us to render older browser versions if necessary. In this case, we are targeting Edge; however this isn't as necessary. 
  - **name** & **content**: Details on the users viewport, or screen, and auto scales as necessary.
  - **title**: details the title of our document. This is displayed in the tab of the browser page.

# Body
  - body: 
      - What the client will display when rendering.
  - img tag has two default attributes
      - src
          - required
          - source of the image. This could be in an assets folder or another location on the web.
      - alt
          - optional ~ but highly recommended
          - text that is used in case image doesn't load.
          - text that is read by screen readers for the visually impaired.
          - can be a source for SEO (Search Engine Optimization)  
      - title
          - can help with tool-tips.
  - input: typically used in forms but not limited. 
      - Many different types such as numbers, radial, email, password, etc.
  link: won't show up in the browser, but is a way for us to connect files such as CSS.