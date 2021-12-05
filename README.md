# Self_help

### for reset radio selection
        window.addEventListener('unload', function(event) {
        document.getElementById("size_div").reset();
        document.querySelectorAll('.size-radio')[0].checked = true;
        }, false);
        
### for reset select option   
        window.addEventListener('unload', function(event) {
        let select_cost = document.getElementById('select_cost');
        select_cost.selectedIndex = 0;
        }, false);
