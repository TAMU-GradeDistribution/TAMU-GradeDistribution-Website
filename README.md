# TAMU-GradeDistribution-Website
This project is dedicated to helping analyze the massive amounts of data released every semester by Texas A&M University's Registrar's office.

---

## Features:
- Blazing fast loading times
- Server and client side caching
- Fully responsive design for desktop and mobile
- Presents a sleek, intuitive, and non-cramped interface
- Presents multiple *useful* forms of analysis for course data

## TODO:
- [ ] Automatically update the database when new data is released

## How to use:
1. Run [TAMU-GradeDistribution-ParserV2](https://github.com/TAMU-GradeDistribution/TAMU-GradeDistribution-ParserV2) to generate necessary database tables
2. Rename example_tamugd_config.js to tamugd_config.js
3. Modify the values in tamugd_config.js to suit your environment
4. Then run the following npm commands:
    ```bash
    # install dependencies
    $ npm install

    # start server
    $ npm start
    ```

---
And you're done!