*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
nav{
    height: 5vh;
    /* if we added flex propertie it will make flex dirction as a row  */
    display: flex;
    /*flex-direction: types 
    1 row and row rev
    2 column and col rev
    */
    /* flex-direction: column; */
    /* justify-content:flex-end; */
    
    background:#808080;
    /* align-items: flex-end; */
    

}
h2{
    display: inline-block;
    background: red
}
span{
    background: #000;
}
ul{
    display: flex;
    justify-content: flex-end;
    width: 20vh;
    gap: 20px;
}
/* ul{
    height: 5vh;
    width: 30vw;
    display: flex;
    justify-content: space-around;
    align-items: center;
} */
/* ul{
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
}
li{
    width: 30vw;
    height: 30vh;
    background: #000;
    color: aliceblue ;
} */