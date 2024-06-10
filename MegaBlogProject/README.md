# React + Vite

# In that project we using appwrite service for our backend and some other things
```
npm install appwrite
npm install @reduxjs/toolkit
npm install react-redux 
npm install react-router-dom
npm install @tinymce-react 
npm install html-react-parser
npm install react-hook-form

```
# Creating env and env.sample files
# 1) All password and password keys are storage in the env

```
VITE_APP_APPWRITE_URL = ""
VITE_APPWRITE_PROJECT_ID=""
VITE_APPWRITE_DATABASE_ID=""
VITE_APWRITE_COLLECTION_ID=""
VITE_APWRITE_BUCKET_ID=""
```
# Now we create a config folder and configure of important keys
```
const conf =  {
    appwriteUrl:String(import.meta.env.VITE_APP_APPWRITE_URL),
    appwriteProjectId:String(import.meta.env.VITE_APPWRITE_PROJECT_ID),
    appwriteDatabaseId:String(import.meta.env.VITE_APPWRITE_DATABASE_ID),
    appwriteCollectionId:String(import.meta.env.VITE_APPWRITE_COLLECTION_ID),
    appwriteBucketId:String(import.meta.env.VITE_APPWRITE_BUCKET_ID)
}
export default conf;
```
