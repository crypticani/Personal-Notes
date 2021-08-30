<script src="https://code.jquery.com/jquery-3.5.1.js" 
          integrity="sha256-QWo7LDvxbWT2tbbQ97B53yJnYU3WhH/C8ycbRAkjPDc=" 
            crossorigin="anonymous"></script>
  
    <script type="text/javascript">
    $(document).on('submit','#task-form',function(e){
        e.preventDefault();
        $.ajax({
            type:'POST',
            url:'{% url "home" %}',
            data:
            {
                task:$("#task").val(),
                csrfmiddlewaretoken:$('input[name=csrfmiddlewaretoken]').val()
            },
            success:function(){
                  alert('Saved');
                    }
            })
        });
    </script>
