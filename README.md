# media.js
Simple media queries for styled components  

---
Implementation example below

```javascript
import styled from "styled-components";
import { media } from "media-js";

export const NavContainer = styled.nav`
  display: flex;
  justify-content: space-around;
  padding: 2%;
  background: transparent;
  z-index: 0;
  font-family: "Oswald", sans-serif;
  ${media.giant`width: 30%;`}
  ${media.desktop`width: 30%;`}
  ${media.tablet`width: 100%;`}
  ${media.phone`width: 100%;`}
`;
```

...more info to come
