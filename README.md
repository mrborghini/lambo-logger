# lambo-logger

```bash
npm install lambo-logger
```

## Usage

```javascript
import { Logger } from "lambo-logger";

const logger = new Logger("Index");
logger.info("Hello, world!");
logger.warning("Warning!");
logger.error("Error!");
logger.debug("This is only visible when DEBUG is true in environment");
```
