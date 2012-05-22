<strong>Init navigation</strong><pre>$(function () {      	            
    var nav = $('#nav > ul');    
    nav.navigation({
        sensity: 5,
        position: [{
            my: 'left top',
            at: 'left bottom'
        }, {
            my: 'left top',
            at: 'right top',
            offset: "-2 -1"
        }]
    });   
});
</pre>