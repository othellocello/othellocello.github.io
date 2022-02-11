#Component

```typescript
class Greeter {}

@Component({
  changeDetection: ChangeDetectionStrategy.OnPush,
  viewProviders: [ Greeter ], // provides a class to the template
  moduleId: '',
  [templateUrl | template]: '',
  styleUrls: [''],
  styles: string[''],
  animations: [],
  encapsulation: ViewEncapsulation.None | ViewEncapsulation.ShadowDom | ViewEncapsulation.Emulated,
  interpolation: ['{{', '}}'],
  preserveWhitespaces: false,
  //inherited from directive decorator
  selector: '',
  inputs: [],
  outputs: [],
  providers: [],
  exportAs: '',
  queries: {
        contentChildren: new ContentChildren(ChildDirective),
        viewChildren: new ViewChildren(ChildDirective)
    },
  host: {
        'key': 'value'
    },
  jit: false
})

enum ChangeDetectionStrategy {
  OnPush = 0,
  Default = 1
}

```
