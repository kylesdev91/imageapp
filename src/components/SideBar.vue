<template>
     <VNavigationDrawer
       expand-on-hover
       rail
     >
     <VList>
          <VListItem
            prepend-avatar="https://scontent-dfw5-1.xx.fbcdn.net/v/t39.30808-1/287835062_480131343871124_1629321482302033099_n.jpg?stp=dst-jpg_p480x480&_nc_cat=105&ccb=1-7&_nc_sid=7206a8&_nc_ohc=imqwPP9IES8AX_-E_Kl&_nc_ht=scontent-dfw5-1.xx&oh=00_AfAaHauVIcK1EqU8niBaM9781-4dwPAeIehgUqdydxeOYg&oe=636F4B90"
            title="Kyle Hernandez"
            subtitle="kyle@gmail.com"
          ></VListItem>
        </VList>

        <VDivider />

        <VList density="compact" nav>
            <VListItem
              prepend-icon="mdi-image"
              title="Color Gallery"
              value="color"
            />
            <VListItem
              prepend-icon="mdi-dialpad"
              title="Grayspace Gallery"
              value="color"
            />
           </VList>
        </VNavigationDrawer>
</template>