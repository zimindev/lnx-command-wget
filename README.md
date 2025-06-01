## ⚡️ **Mini list `wget` Command**

### 📥 **Basic Download**

```bash
wget https://example.com/file.zip
```

* Downloads `file.zip` to current directory.

---

### 💾 **Save with Different Name**

```bash
wget -O custom_name.zip https://example.com/file.zip
```

---

### 📂 **Download to Specific Directory**

```bash
wget -P /path/to/dir https://example.com/file.zip
```

---

### 🔁 **Resume Download**

```bash
wget -c https://example.com/largefile.zip
```

* Resumes partially downloaded file.

---

### 🚦 **Follow Redirects**

```bash
wget --max-redirect=10 https://example.com
```

---

### 🔐 **Skip SSL Verification**

```bash
wget --no-check-certificate https://example.com
```

---

### 🗂 **Download Entire Website**

```bash
wget --mirror -p --convert-links -P ./local-site https://example.com
```

* Full site mirror with assets (`-p`), relative links (`--convert-links`).

---

### 🕸 **Recursive Download**

```bash
wget -r https://example.com/dir/
```

* Downloads all files and subdirectories.

---

### 🧾 **Download File from List**

```bash
wget -i filelist.txt
```

* `filelist.txt` contains URLs (one per line).

---

### 🔐 **Add Headers / Auth**

```bash
wget --header="Authorization: Bearer TOKEN" https://example.com/api
```

```bash
wget --user=USERNAME --password=PASSWORD https://example.com/protected.zip
```

---

### 🧰 **Set Download Speed Limit**

```bash
wget --limit-rate=200k https://example.com/file.iso
```

---

### 🔄 **Retry on Failure**

```bash
wget --tries=5 https://example.com/file.zip
```

---

### 🐾 **Verbose & Quiet Mode**

```bash
wget -v https://example.com         # verbose (default)
wget -q https://example.com         # quiet (no output)
```
