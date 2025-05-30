
function showForm(formId) {
    document.querySelectorAll("form").forEach(f => f.style.display = "none");
    document.getElementById(formId).style.display = "block";
}

function saveForm(formId) {
    const form = document.getElementById(formId);
    const inputs = form.querySelectorAll("input");
    let data = formId.charAt(0).toUpperCase() + ',' + Array.from(inputs).map(i => i.value).join(',') + "\n";
    const blob = new Blob([data], {type: "text/plain;charset=utf-8"});
    const link = document.createElement("a");
    link.href = URL.createObjectURL(blob);
    link.download = "input_data.txt";
    link.click();
}
