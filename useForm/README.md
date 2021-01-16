#useForm Hook

Ejemplo 

```
    const initialForm = {
        name: '',
        age:0,
        email:''
    }
    
    const [formValues,setFormValues,handleInputChange,reset] = useForm(initialForm);

```