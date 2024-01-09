# Redux toolkit
1. useSelector for selection    
2.  useDispatch for sending  //both are from react
3. reducers is a object
4. create a folder for store and create a file in it store.js .
5. import configureStore from pure redux
6. export it by storing in a variable/constant plus configureStore always take object 
7. create reducers in redux toollkit known as slice . create a folder then a file name  it with Slice just for info that you are using redux toolkit and now  import the slice
8. nanoid generate unique id
9. define initial state
10. export slice and in createSlice you will given name which will be shown in redux devtools,same name
11.  state is what is available in state now.
12.  value comes  from action means data
13. have to export 2 more time slice with reuducer and individual reducer too
14. give info tp store
15. dispatch use reducer and add or change value in store
16. import { Provider } from 'react-redux'
import {store} from './app/store'


ReactDOM.createRoot(document.getElementById('root')).render(
  <Provider store={store}>
    <App />
  </Provider>,
)