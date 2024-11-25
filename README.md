# **Medical Imaging SaaS Application**

This project is a SaaS application designed to assist lab technicians in the healthcare sector with medical image annotations, measurements, and geometric calculations. Built using React.js, the application provides a neat, clean UI, efficient navigation, and robust tools for processing common image formats like PNG.



### Requirements

- [Yarn 1.17.3+](https://yarnpkg.com/en/docs/install)
- [Node 18+](https://nodejs.org/en/)
- Yarn Workspaces should be enabled on your machine:
  - `yarn config set workspaces-experimental true`



#### To Develop

_From this repository's root directory:_

```bash
# Enable Yarn Workspaces
yarn config set workspaces-experimental true

# Restore dependencies
yarn install
```

## Commands

These commands are available from the root directory. Each project directory
also supports a number of commands that can be found in their respective
`README.md` and `package.json` files.

| Yarn Commands                | Description                                                   |
| ---------------------------- | ------------------------------------------------------------- |
| **Develop**                  |                                                               |
| `dev` or `start`             | Default development experience for Viewer                     |
| `test:unit`                  | Jest multi-project test runner; overall coverage              |
| **Deploy**                   |                                                               |
| `build`\*                    | Builds production output for our PWA Viewer                   |  |

\* - For more information on different builds, check out our [Deploy
Docs][deployment-docs]




## **Features**
 **Neat and Clean UI**  
   - Intuitive and visually appealing design.  
   - Easy navigation and user-friendly interface.

 
 **Key Functionalities**  
   - Annotate regions of interest in images.  
   - Measure geometric shapes like circles, ellipses, and angles.  
   - Optimize images with basic manipulation tools (zoom, crop, pan, etc.).

---

### **Serve the Production Build Locally**
To preview the production build locally:
```bash
npm install -g serve
serve -s build
```
The app will be accessible at [http://localhost:5000](http://localhost:5000).

---

## **Technology Stack**
- **Frontend Framework**: React.js
- **State Management**: Redux API
- **Styling**: Tailwind CSS
- **Hosting**: Netlify

---

## **Future Enhancements**
- Add support for DICOM image formats.
- Advanced image manipulation tools like brightness and contrast adjustments.
- User authentication and role-based access.

---


