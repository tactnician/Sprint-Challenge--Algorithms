
### Understand 

1. Matching Methods
    
    * can_move_right = range(arr) -1
    * cam_move_left =  self.position > 0

    * move_right = i+=1 
    * move_left = i-=1

    * swap_item = item, position = position, item
    * compare_item  => 
        if is none => none, 
        elif > return 1, 
        elif < return -1
        else return 0 

    * set_light = toggle bool 
    * light_is_on = return bool 

1. Sorting Algorithim = Bubble
    def bubble(r):
        n = len(r):
        for i in range(n):
            for j in range(0, n-i-1):
                if arr[j] > arr[j+1]:
                    arr[j], arr[j+1] = arr[j+1], arr[j]


### Plan 

    * def bubble(r):
        can_move_right 
            can_move_right 
                compare
                    if compare 1:
                        swap
                    if compare -1:
                        swap
                        move_left
                        

        
    

### Execute 



### Optimize 

