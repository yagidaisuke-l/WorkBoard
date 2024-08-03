### コンポーネントの追加方法

コンポーネントを作成する
```bash
ng generate component component-name
```

ルートをインポートする
```bash
import { FirstComponent } from './first/first.component';

export const routes: Routes = [
  { path: '', component: FirstComponent },
];
```

ページ内でリンクを設定するだけです。