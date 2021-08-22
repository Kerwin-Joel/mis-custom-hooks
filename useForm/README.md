# useform ejemplo
```
const [values,handleInputChange,reset] = useForm(initialState = {})
```

Ejemplo : 
```
const [values, handleInputChange] = useForm({
        name: '',
        email:'',
        password:''
    })

const {name,email,password} = values;

<input 
    type="password"
    name="password"
    placeholder="******"
    value={password}
    autoComplete = 'off'
    onChange={handleInputChange}
/>

```
# Reset es un metodo para limpiar los valores y por defecto los campos se limpiaran