
### Directory Structure

```plaintext
tnm/
|- tnm-db/
   |- docker-compose.yml
   |- db_data/
   |- init-scripts/
      |- 01-init.sql
```

### 1. Clone the Repository

```bash
git clone https://github.com/alpaii/tnm-db.git
cd tnm-db
```

### 2. Start the DB Container

```bash
docker-compose up -d
```

### 3. Connect to the DB

```bash
mysql -h 127.0.0.1 -P 3306 -u user -p
```


