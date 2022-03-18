# useForm Hook

Usage Example:

```
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    }

    const [ formValues, handleInputChange, reset ] = useForm(initialForm)
```

The inputs fields names must match with the initialForm object's names properties to work.
