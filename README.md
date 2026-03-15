# swiss_knife 🔪
A standard library extension for c++ to include some of the popular algorithms.

---

## 📥 Installation (Header-Only)  
### Option 1: Clone Just the `knife/` Folder  
```sh
# Clone ONLY the aggregator header (no submodules/tests):  
git clone --filter=blob:none --no-checkout git@github.com:CodeGeek2006/swiss_knife.git  
cd swiss_knife  
git sparse-checkout init --cone  
git sparse-checkout set knife  
git checkout main  # or your target branch  
```

### Option 2: Download Manually  
1. Go to [`knife/` on GitHub](https://github.com/x2lol/swiss_knife/tree/main/knife).  
2. Download the header file(s) you need (e.g., `swiss_knife.hpp`).  

---

## 🛠 Usage  
1. **Include the aggregator header** in your project:  
   ```cpp
   #include "path/to/knife/swiss_knife.hpp"  // Or copy to your project
   ```
2. **Compile with C++17 or later**:  
   ```sh
   g++ -std=c++17 your_code.cpp -o your_program
   ```

---

## ❓ FAQ  
**Q: Why ignore other folders?**  
- `/tests/`, `/submodules/`, etc. are for development. End-users only need `knife/`.  

---

## 📜 License  
MIT License. See [LICENSE](https://github.com/x2lol/swiss_knife/blob/main/LICENSE).  

---

### 🔗 Links  
- [Full Repo](https://github.com/x2lol/swiss_knife) (for developers)  
- [Report Issues](https://github.com/x2lol/swiss_knife/issues)  

--- 
