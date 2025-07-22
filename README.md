// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyBXQ3Hd2uQJC5RhOJ0s760KX7PWckKTwcU",
  authDomain: "levelquiz-3ca4d.firebaseapp.com",
  projectId: "levelquiz-3ca4d",
  storageBucket: "levelquiz-3ca4d.firebasestorage.app",
  messagingSenderId: "1017358592092",
  appId: "1:1017358592092:web:0345374a79363f3d0f9e99",
  measurementId: "G-1NXQXNVDZD"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
