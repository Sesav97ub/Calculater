# Calculater
function AlgebraModule() {
...
return <>
<Button
operation={(a, b) => a + b}
name="Add"/>
<Button
operation={(a, b) => a - b}
name="Subtract"/>
<Button
operation={(a, b) => a * b}
name="Multiply"/>
<Button
operation={(a, b) => a / b}
name="Divide"/>
<div>
{result}
</div>
</>;
}
