
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
git clone <repository-url>
cd tnm-db
```

### 2. Start the MySQL Container

```bash
docker-compose up -d
```

### 3. Connect to db

```bash
mysql -h 127.0.0.1 -P 3306 -u user -p
```


