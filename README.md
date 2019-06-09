# XSKY KOA API

## Flexible Koa API

### Installation

**npm version >= 5.2.0**

```bash
npx xsky-koa-api koa-api
```

**npm version < 5.2.0**

```bash
npm install --global xsky-koa-api
xsky-koa-api koa-api
```

### Configuration

**Change directory**

```bash
cd koa-api
```

**Copy .env.example to .env and change data**

```bash
cp .env.example .env
```

### Migration

**Create, migrate and seed**

```bash
npm run db:migrate
```

**Drop**

```bash
npm run db:drop
```

### Linting

**Check lint issues**

```bash
npm run lint
```

**Fix lint issues**

```bash
npm run lint:fix
```

### Validate

**Validate application**

```bash
npm run validate
```

### Run

**Run in development**

```bash
npm run dev
```

**Run in production**

```bash
npm start
```

### License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
