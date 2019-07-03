# LAB - 37

## One-to-Many relationships in Redux

### Author: Joé Jemmely

### Links and Resources

- [CodeSandbox](https://codesandbox.io/embed/lab-37-cl4rl)

### Documentation

#### Country

##### Create

```javascript
{
type: 'COUNTRY_CREATE',
payload: {
  id:0,
  name:'ch'
  }
}
```

##### Update

```javascript
{
type: 'COUNTRY_UPDATE',
payload: {
  id:0,
  name:'us'
  }
}
```

##### Delete

```javascript
{
type: 'COUNTRY_DELETE',
payload:{id:0}
}
```

#### State

##### Create

```javascript
{
type: 'CSTATE_CREATE',
payload: {
  countryId:0,
  id:0,
  name:'fribourg'
  }
}
```

##### Update

```javascript
{
type: 'CSTATE_UPDATE',
payload: {
  countryId:0,
  id:0, name:'bern'
  }
}
```

##### Delete

```javascript
{
type: 'CSTATE_DELETE',
payload: {
  countryId:0,
  id:0
  }
}
```

#### UML

Coming soon
