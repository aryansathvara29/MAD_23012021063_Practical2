# MAD Practical – 2 : Activity Life Cycle & Basic UI

This Android application demonstrates the **functions of the Activity Life Cycle** along with creation of a simple UI using a centered `TextView`.  
The practical focuses on understanding lifecycle callbacks, UI properties, logging, and use of Toast/Snackbar messages.

---

## 📌 AIM  
Create an Android Application to demonstrate functions of **Activity Life Cycle** and **Basic UI**.

---

## 📝 Tasks Completed

1. Created an Activity with:
   - Yellow background: `android:background="#FFFF00"`
   - A centered **Hello World** `TextView`
   - Text color: `@android:color/holo_blue_bright`
   - Font size: `27sp`
   - Text style: **bold & italic**

2. Demonstrated **all Activity Life Cycle methods**:
   - `onCreate()`
   - `onStart()`
   - `onResume()`
   - `onPause()`
   - `onStop()`
   - `onRestart()`
   - `onDestroy()`

3. Displayed lifecycle events using:
   - **Log messages**
   - **Toast messages**
   - **Snackbar messages**

4. Ensured all lifecycle methods print their status in **Logcat**.

---

## 📚 Study / Concepts Used

This practical includes the following Android concepts:

### 🔹 **UI Components**
- `TextView`
- TextView properties:  
  `android:textColor`, `android:textSize`, `android:textStyle`, `android:gravity`

### 🔹 **Layout**
- `ConstraintLayout`
- Setting background color  
- Setting layout constraints  
- Generating view IDs

### 🔹 **Activity Life Cycle**
- Understanding all lifecycle callback methods  
- Execution order of lifecycle methods  
- Logging lifecycle events

### 🔹 **Messages**
- **Toast** messages  
- **Snackbar** messages  
- **Logcat** with `Log.d()` / `Log.i()`

### 🔹 **Resources**
- Android in-built color resources such as:  
  `@android:color/holo_blue_bright`

---

## ✨ Features

- Clean UI with a centered “Hello World” message  
- Background color applied using XML  
- Text styling (bold, italic, size, color)  
- Lifecycle method tracking using:
  - Toast  
  - Snackbar  
  - Logcat output  
- Helps visualize how Activity transitions through states

---

## 🚀 How the App Works

1. Launch the app → **onCreate → onStart → onResume**
2. When the user presses Home → **onPause → onStop**
3. Returning to the app → **onRestart → onStart → onResume**
4. Closing the app → **onPause → onStop → onDestroy**

Each method triggers:
- A **Log message** in Logcat  
- A **Toast** showing the method name  
- A **Snackbar** displaying lifecycle information (visible in UI)

---

## 🏗️ Project Structure


<table>
  <tr>
    <th>Xml UI:</th>
   
  </tr>
  <tr>
    <td><img width="209" height="370" alt="Screenshot 2025-08-15 194103" src="https://github.com/user-attachments/assets/86250571-3a8e-4584-a1d7-f2d52652bbda" />
</td>
    
  </tr>
</table>
